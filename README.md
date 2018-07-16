![Alt Text](https://imgur.com/f9sexkJ.gif)

1. Fork/Clone

1. Sign up for [Stripe](https://stripe.com/) (if you don't already have an account).

1. Set the Stripe Secret [key](https://stripe.com/docs/keys) as an environment variable:

    ```sh
    $ cd server
    $ export STRIPE_SECRET_KEY=UPDATE_ME
    ```

1. Run the server-side Flask app in one terminal window:

    ```sh
    $ cd server
    $ python3.6 -m venv env
    $ source env/bin/activate OR source/Scripts/active (this depends on your environment)
    (env)$ pip install -r requirements.txt
    (env)$ python app.py
    ```

    Navigate to [http://localhost:5000](http://localhost:5000)

1. Update `stripePublishableKey` with the Stripe Publishable [key](https://stripe.com/docs/keys) in *client/src/components/Order.vue*.

1. Run the client-side Vue app in a different terminal window:

    ```sh
    $ cd client
    $ npm install
    $ npm run dev
    ```

    Navigate to [http://localhost:8080](http://localhost:8080)
