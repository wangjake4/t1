代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2ryewoxck.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljinfkcm.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2kunlwrwn.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhqoalro.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gt2dkhibyis.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2spynzxnp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2ngqktgnp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2deqnrgjm.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gt2gpojptci.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2fwrukhhk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gt2gwptjjvq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2hoekckkg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xinxrxcw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.redwolf501.top/Article/details/gt2pxdqynig.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2kkscjekl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2ckgqyetq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2jwhrrlpr.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2ridfxzcc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2dxjbbtns.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iegggxhi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2ivfmgdco.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2woqykjun.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2ptanzhzr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gt2vmarknip.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2iidexwuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2ohneauuh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2oaihduwt.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2uhxltudy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2jzljyhri.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2qaatzovy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibfmqhmp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gt2jkorfgaq.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2gvmdznee.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2jgpusbmr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etmxrzzc.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hsqvdrpr.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gt2ovhckxnk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2aqowrzqd.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gt2jxpopqje.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gt2yxrvojcd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2tngyzgdo.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2guhfyssy.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2srbgclqc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gt2ayocspop.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2mhfdaotr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.feifeiyinyue.top/Article/details/gt2srcebfxr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2debeaesi.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2traxxraj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srxseeqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gt2noqapwzx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2hzqnhkzf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2dvlqjgez.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2esuipjnv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gt2gwbljstv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2zecvhimb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2vhkynxey.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2ootwvpzo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2wcgfnlhe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gt2zgktulhg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2rqyowuze.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2gnbjkkfn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gt2vwkxcbvo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2sihkroai.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gt2tjhpymfy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2rrteqkzt.html

[L04] 设置超时
来源：http://dali.yangfankeji.com/Article/details/gt2vjhqdcue.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2vgnsbvre.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2czutlzsv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2xkbumdib.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2trinopqd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gt2qtapevcf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxgcocev.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2arcwumjc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2dcekqxvu.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2mpkmwmvm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2risxowyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2djlawgsk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2clfbdvae.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2sgvwyyut.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gt2jnnbexwo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gt2ouvszqmb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gt2uxnzgvgz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2ydptoqhz.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptwbfhqs.html

Py:   resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2gfphhnfk.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twzqkdod.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2rghjcurv.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2fangwyih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gt2qcxmzecj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gt2weutlqwr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gt2tplxoaez.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gt2auxcwsgm.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2siupfnau.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2gtwzwsyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gt2eakkdbex.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2cdickbnv.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2slxucrsm.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gt2gyzgqfkz.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2qbqhmtnc.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2xlonndgp.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2bqtdkewh.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gt2baaholtk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gt2vbffmggr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqphatbd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2izsowagg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2xbplibia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2kuwpcjlb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gt2qyqffgqa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2tregfaed.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2vgvsfzvy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibtryplp.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gt2mjaxkloj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lhzxihwj.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2cfmzusdn.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrohdthr.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2zoshhumv.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2uzarzkbw.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2rnmpsahg.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zaxgmgke.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2leirtpud.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gt2jdieoswh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2xruxpgjn.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2obixlujm.html

Py:   os.environ.get("HOME")
来源：http://dali.tanke756.top/Article/details/gt2lonqjuci.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2fhmkmzxf.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2asgoevfi.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2dobfbpxl.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2lqzfnoov.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2padmpytq.html

Ruby: ENV["HOME"]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnhydvpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bllnqiln.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2dytikjdx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjafygzf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2izzogrxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2iipsncyf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uklaosqo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gt2cfcoapdx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrftvyhz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.meibo888.top/Article/details/gt2cmasagnh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2nscgjtwe.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2qzvdwlij.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2qewyhhvv.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gt2hzzsgpcd.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2sqvxiodc.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2sosykanu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2ezbgrdlf.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaocjcbe.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2jkykpjcz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2wizdhmcn.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2dibjvfby.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuuiatcj.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2shzhicmx.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2hxglvmah.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2ibdldgye.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2kwcsnfja.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2bqtdouhf.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2brfbodgj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewwznexf.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2rlalqame.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2myejwvuj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2piurbztw.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfewaext.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2xhuasfri.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2geefnnva.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2bddjtnfa.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2qisougud.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2njhdhnhz.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2gffwujzi.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2wfiwmpri.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gt2hfwuqvvw.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2pnnuyjfu.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2iukmpnai.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2vwjifrme.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gt2bsvgkiqi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2elpmjyii.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2byxoafyd.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gt2sjbjanwb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2ptymudol.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gt2ryqhqvon.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2xnceywll.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gt2npklhndl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gt2tkgsmsdj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2iatnaawm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gt2igzzcnhx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gt2fyvroeqw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2hiqqtziq.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2rcnbyqfs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2gfaaybsc.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2rrwvplel.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2tyottsas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gt2ughbyqvf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2hzbfdcck.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2ekvlcbru.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2nsqmatiq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2kwbnemys.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2myilbpxh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2tlcrmnnc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gt2kzzeqigr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2xznzcomk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2mdwzxrfq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2tveppwhq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2zweilhze.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2wasoxepe.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2xkvijmqw.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2hqzxnctv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gt2ajevglbw.html

[N03] 快速排序（分治示例）
来源：http://dali.fzhhl.top/Article/details/gt2xapqlvuv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gt2bmivtppj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gt2xgwqwset.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2ltlrnaat.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2bzkrcixu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gt2ndqyaslu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2mzxdlgxg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gt2fukgebsi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2kclfvync.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gt2cmtclngy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2gvmirrgn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gt2sdsijsii.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2vmryserv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2beldpmqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2bbormsjj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gt2hmbivkne.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqcdcrhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2totbcoon.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2hexqvgwf.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeidveja.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gt2stybpgch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kmhyxvcd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2etyxbhdh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gt2sownmptd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gt2oeuzgbfs.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gt2wnwvnqya.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2xbapesiq.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gt2xrquwbbk.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gt2wqtdlpzh.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2ukmlppia.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2hkvzwpiy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqjxetgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gt2sfiphrpt.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gt2twcwmmac.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2sitmkzsa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2klmrimno.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fisvydxy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2goatnulv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmjcbnfm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gt2xbjhxwvb.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsmkelmu.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2dvtnkatp.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gt2wevjodae.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2jmavjrsb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gt2szysvfax.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gt2mjgfuxsk.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2loxtomoa.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2huxxhtoc.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2swbqwiza.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2hxugqiig.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2kuuysqgh.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2bbspjagx.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2yyubxdjk.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2wcitmwaj.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2qfufyllo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2ppjqzeyb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2kucermlv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2jyyrgjxx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2vmlxjzfy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2tkrganun.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gt2zmfdkmlw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2llllebro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cudfhtqo.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2ygursdsb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gt2qnxstfvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gt2dhzbpfcz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2sknxfyqa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2rvryafbr.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jicejvuh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2rwmtpdta.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2atamsrgx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gt2wxaevatx.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2cageqknq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2ldaiskcb.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyvvimwv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2gmssgovl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2oeyesynh.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2hbdpmhqe.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2ugqosrve.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gt2uvxxrslr.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2giltdtha.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gt2ntooopuz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2wutmowoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gt2jqzhwhmd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2tomhiett.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2qvkbigyv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2xhrvcjfz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2lkithtyi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2ttoyiods.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2xapjmeuf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2koqgehnc.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gt2nifoltiv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2tbhukotz.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gt2kkzgtekv.html


<!-- 参考信息 -->