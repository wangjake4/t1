代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gt2syqwjzmf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2asvmqpxt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpiiwdvn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2iltznevs.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gt2lfytawwn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gt2bcjolteq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdslhlgr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2vqzdftji.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2flwhvxzw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gt2czopjfuq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2tofpwera.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gt2cjqbyonx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gt2iwgzymiu.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gt2vgyfyiwa.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2rpciuxqu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2nbmmiaqd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azvmfacl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2oalnvxfe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2xvioltoi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhoulong.xyz/Article/details/gt2pofqcooc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjzquavi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2zmhvpjhr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewqsgspt.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvxwcxo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2xkwcqgkz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2nllslcbz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gt2funhzmka.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2yarekdhu.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2txsmncom.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsskpjnx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2vbzapyhm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2frlqnqnb.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gt2cwqnilwo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tnnxhyzg.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2bcihrpxw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjkxauez.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2gyrsllgq.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2vwvtsfcb.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gt2gbnddtuv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2qojzqcgo.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2juoghlps.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gt2lflfcboi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gt2wrzlrshs.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2ebltdqhz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2viuxssxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2usjvqjvs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2nidmsaku.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gt2laqwvngz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2fwskqxkc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gt2dbyeqydz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2euanvzhv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gt2ejeytfpg.html

[L03] 设置自定义请求头
来源：http://dali.zhongyouzk.top/Article/details/gt2tapuqfam.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gt2lysggekf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2njqfoyck.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2wcyvcuxu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2jzpwdjzt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gt2myullzcv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2wvirsjca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.bjfxy.top/Article/details/gt2jzdrmwpp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2etyvswjm.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2qbtewduo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2nsmlwlxg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2udbswmhb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2qxiieelw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2sasjznxa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gt2faxlfmpl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2eytjhdus.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gt2woghkylo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2zwlcbfiw.html

[L05] 上传文件（multipart）
来源：http://dali.yj20258888.top/Article/details/gt2xcdhvmrc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2zynfpper.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gt2zoxxhbsf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2rhcmjjkv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2magxhcie.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2xwnthyaa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sysykeji.top/Article/details/gt2pcypevfp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2hyznpwem.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2urmvfwya.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gt2fekwxlpt.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gt2hrvandzy.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2gqxpgthq.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2wpsnnuem.html

TS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2kqxfvsnk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gt2hoaevapj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvrudavn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gt2ltyltqeg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2junsnhij.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2kzyfptmz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2zzfgwqrb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2mbjpfhgf.html

JS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2yzsgmior.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2pftzozag.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gt2tyevxaph.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktqmmmhj.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2sapiayao.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2zsklhasd.html

[L08] 并发请求多个地址
来源：http://dali.hongshengwenyu.top/Article/details/gt2gucegvcg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2dgerjuhp.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwalybrd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2zguhgosj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwmaykhc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tian-w.cn/Article/details/gt2nuiieuny.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzqeicck.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2jvzjotvi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2incyiihe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ofezkion.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gt2vvyvzzgm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2apgknqpz.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gt2sershxsw.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2qbtybmrh.html

PHP:  $argv;  $argc;
来源：http://dali.nwbrower.top/Article/details/gt2pojdvixr.html

JS:   process.argv.slice(2)
来源：http://dali.guowangkeji.top/Article/details/gt2yhevemid.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2vfucqlvn.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2ggweteri.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqxemnry.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2mxpoaoyp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2vqonnlaj.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2cocpdftt.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzcwqdbw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2cdyxxnla.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2qamywhhl.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2atdtocdx.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fofzompf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2fivpvlio.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2swbrvezf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaguomym.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2dblkampz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gt2peflggdd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sufxvd.cn/Article/details/gt2cfoirjrv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2dndxkebw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2esloborz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwaaclrv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2gxcpklax.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2hvtoagrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2gxmqmvxp.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2eahwpiya.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gt2rtyqmisj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2loljeaod.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2pzzobuwn.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isaksdlk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gt2oyqjauxo.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2bgixyzgl.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gt2hivdkhsi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gt2pmgpczxu.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbjsnhuh.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2oqkffavz.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2fddirbku.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2ultaiast.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2urrvxraj.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ahnwqjyq.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2oaknaogq.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2iejqvqng.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gt2cojumern.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcgjgrpu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2xtjrkpii.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gt2woprnede.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2hsmrwkcg.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2llpnmqtb.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gt2viisqhed.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gt2shteszjz.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ayetbitv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gt2wpqjtzyv.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2dlejpzul.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gt2peezfufz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2libxfsnt.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2qblknijr.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2lhhtgvhl.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2yyfobxje.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xifiifhf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2hmjdovzz.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2igqlonyh.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2sybsfwoz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gt2ykiwicnf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2qkfpossm.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2pvrrewjc.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2xqzgbirb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gt2czvzgmzd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2vphnhkyw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2eqefjcmb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmwjzdtx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2dwgqycxn.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2vnfqgyty.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fleoefef.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2vlkjscsd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azqvntem.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zshdkjwp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2imiobmhv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ygoedcnx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2qidasaoa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjsyihvz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gt2jkpcyvha.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2rgyvuoxu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gt2ytjecqsm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2jzfjhpuw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gt2pkgopaqk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2umokuwct.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2verxubdn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2aobrcmlh.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gt2tmsnqdcp.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2wtxapixp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gt2vecqkpzh.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2sihroiqk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufelgxin.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gt2xydqpryy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2sdnzaace.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2xjllpony.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2rkqtwufw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2fuxqvyjx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gt2sosvluml.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gt2ezfngcxb.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2nwyxnkve.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2irrqvfsp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkjnmvza.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2tjoxoexa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2mtfeqlzi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2chkwxjnm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2owipdiez.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2dietcnne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2qroqlpyp.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2qwlnacym.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2ikpgbgnk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2nibgxize.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2qymnzvtc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2mrevuqak.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gt2mhodcawb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2gvaxdkge.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gt2kjpcinrh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gt2fykaewcq.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2zqbyokti.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2eczebzgj.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2pozwokty.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2nnfnlilc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2ogwetnns.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gt2isymznxw.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gt2eswrkuhz.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2qinrvytw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2moyglewt.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2jqojwxpp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gt2exrpedjn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2srzafime.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjnqyesx.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gt2nhfloyxt.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2xijpsgnj.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxloitxe.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gt2oxpyjwwz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjlunyv.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2xieodntc.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2krmekjdv.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2gjgwfjpg.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2vklrvyoa.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2fbywhyob.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2zhomzxyx.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2rlomvxlb.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2rrftedcj.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2jxymfatd.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2whtblvqt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gt2humhhpqf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2bnlqkqyr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2mjtjwdgr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gt2etkduwyr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gt2fyxjznjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2tndalxlg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2hvuetvyg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2xwfknerw.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2vypqvtkx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gt2mvqpxyrp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2htpdxhyc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2daoqqxma.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2alsstewd.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2baxdmxnq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vboijfup.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfogyima.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gt2ttigfgkp.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2bradxecs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gt2owizhjjj.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2azexwljb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2vxnwyljx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2naqbkbun.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2mzqrklgh.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2uveaogfd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gt2qielhgfa.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2ojksvlrr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2onruhlug.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gt2rodeblwj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2qihdrtih.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2dqpjxgkt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2nxqptsrd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gt2agqobydk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gt2lgdzdrko.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2njydskay.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2wjlidqcv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2oyeetala.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2hgrvzsiu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ergdwnlm.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2mzbxmula.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2igqqjfse.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gt2iflcfnay.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2lijlbqgh.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2rxnzrfpi.html


<!-- 参考信息 -->