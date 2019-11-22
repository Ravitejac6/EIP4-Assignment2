# EIP4-Assignment2

Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 13s 222us/step - loss: 0.5291 - acc: 0.8520 - val_loss: 0.0983 - val_acc: 0.9806
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 10s 170us/step - loss: 0.2527 - acc: 0.9281 - val_loss: 0.0856 - val_acc: 0.9828
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 10s 170us/step - loss: 0.1970 - acc: 0.9416 - val_loss: 0.0533 - val_acc: 0.9862
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 10s 171us/step - loss: 0.1683 - acc: 0.9473 - val_loss: 0.0438 - val_acc: 0.9895
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 10s 169us/step - loss: 0.1509 - acc: 0.9507 - val_loss: 0.0354 - val_acc: 0.9905
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 10s 169us/step - loss: 0.1388 - acc: 0.9513 - val_loss: 0.0360 - val_acc: 0.9907
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 10s 169us/step - loss: 0.1304 - acc: 0.9525 - val_loss: 0.0278 - val_acc: 0.9919
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 10s 170us/step - loss: 0.1250 - acc: 0.9535 - val_loss: 0.0283 - val_acc: 0.9922
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 10s 168us/step - loss: 0.1184 - acc: 0.9542 - val_loss: 0.0279 - val_acc: 0.9921
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 10s 168us/step - loss: 0.1112 - acc: 0.9564 - val_loss: 0.0207 - val_acc: 0.9940
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 10s 169us/step - loss: 0.1081 - acc: 0.9555 - val_loss: 0.0306 - val_acc: 0.9916
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 10s 170us/step - loss: 0.1054 - acc: 0.9555 - val_loss: 0.0216 - val_acc: 0.9938
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 10s 168us/step - loss: 0.1028 - acc: 0.9561 - val_loss: 0.0223 - val_acc: 0.9933
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 10s 169us/step - loss: 0.1007 - acc: 0.9576 - val_loss: 0.0214 - val_acc: 0.9936
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 10s 169us/step - loss: 0.0976 - acc: 0.9586 - val_loss: 0.0245 - val_acc: 0.9934
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 10s 170us/step - loss: 0.0947 - acc: 0.9586 - val_loss: 0.0210 - val_acc: 0.9939
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 10s 169us/step - loss: 0.0933 - acc: 0.9586 - val_loss: 0.0213 - val_acc: 0.9930
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 10s 169us/step - loss: 0.0958 - acc: 0.9579 - val_loss: 0.0200 - val_acc: 0.9939
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 10s 169us/step - loss: 0.0918 - acc: 0.9571 - val_loss: 0.0188 - val_acc: 0.9943
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 10s 169us/step - loss: 0.0910 - acc: 0.9580 - val_loss: 0.0185 - val_acc: 0.9940
<keras.callbacks.History at 0x7f4b8156e320>



score = model.evaluate(X_test, Y_test, verbose=0)
print(score)

[0.018499813851737417, 0.994]
