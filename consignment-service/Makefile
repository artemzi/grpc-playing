build:
	protoc -I. --go_out=plugins=grpc:$(GOPATH)/src/playground/shipper/consignment-service \
	  proto/consignment/consignment.proto