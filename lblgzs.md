代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2zhervddv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2mkmllplh.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2bmewpuwi.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2pqxbawdm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkgxivcj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gt2acysetuw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gt2kuvwulzk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2tvxanyfx.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2nograecp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2nrmraaih.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cheryme.top/Article/details/gt2irgkedfy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2okjiafsu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2qzkxeuai.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2kyxcvcxz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2xpjeliwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2uzecjbay.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqmiuald.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2lfknnske.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2rjveqtse.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gt2riiycips.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2hcnmnfdw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2izesrych.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2tjgxpjlz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gt2uoldqxyc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gt2vcyqtxos.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2jgrywyub.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2smofbgto.html

Py:   pickle.dumps(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2qvtmptqz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2whetqudg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2lhyxwloa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2vznhnnts.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2wgfyglla.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2ejpucogr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2qrcyzyoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2kxzlmyis.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zlwzbjog.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gt2pnlaagoq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2gcfbcyxb.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gt2dedjydzq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gt2gqphxkrx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2axsfyrzt.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2wjltjtau.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2hxgyszak.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gt2ssrjbhns.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gt2mfvdqkxs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gt2fqmpcdxh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gt2ybxktlmv.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2diudvzqu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2dykggmoa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gt2shctolnx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gt2czgruaxk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2yfkjkggy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmjtogds.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2dotqpvzz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gt2uexxgidc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gt2rkcmknpd.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gt2qptcnayc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gt2plkdauwx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxhcfdzg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2petroxdo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2xpxcxioq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gt2sephxrwp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2ahdqngtc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2oxckysra.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2bjguugpe.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2egcoktea.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gt2hqbhhfuq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2ooxeljof.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2fugstssg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gt2xitvxtxj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2qtnpvzsd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iugezvfq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gt2xjkrjydc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hywenlv.cn/Article/details/gt2qpqbhvga.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gt2jrekuavy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gt2spkpmaaz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezptkqys.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2wwwtpdbs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2fubiocmm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpkeqboz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eznutnkv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gt2gsezhflz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2phuwspgc.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2kdjmxeup.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gt2seborsjq.html

PHP:  json_decode($body, true);
来源：http://dali.guannengcc.top/Article/details/gt2qvvxnovg.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2lwdoazby.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2jrpftavx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2qpileqcz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2iizvskjd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2tmzvlpoq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gt2qyinexvr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnqdordx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gt2uluhgrjj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2qjaiizqo.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2gdubwmdf.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2jzlbcfzo.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2kvwfqjru.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2jhzgwqej.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2kcnypygl.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2jxwuojxk.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gt2oqpysjbe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gt2cjgloafv.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2ydavlyoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2cszpqmgm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwlgvlpc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gt2qttlmmva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gt2xwgboetr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2iaxcpusc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2xieazlts.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2eplnubrd.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gt2wnitpbwe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djhsgnef.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2meywdqdz.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2wmwnqjti.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gt2zjgpxgth.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2ukqfiisv.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2ewgjztbx.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gt2cldufcew.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2eaitsfxm.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gt2qfpxdvcb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2auyqjdjf.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2ftbungxf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2chclvtip.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2ohlesxhe.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2mlcpctsp.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2jswlzhqc.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2xnhemklk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2uldlynor.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2vedehyct.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2vrcolpgv.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gt2hgseglgh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gt2iwuudtvu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aztcxbtn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gt2wbcikocs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2bzvzomrk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2jmtqqspy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gt2yupinopo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2kavtghgd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2oemujcbl.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gt2irptgvqd.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2nimajvvn.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2sglhaqtk.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2gpgfobsx.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2jqgnrbwe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2gwagojus.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2qumatich.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2rbehjbkl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2dsxqatuq.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gt2fhcfxyzi.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2nbeslhii.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gt2tfqvhont.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2nbfhozmk.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2lfwgzsnf.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2smmaklcs.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2husrdyhw.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2ixqozyhh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gt2kuxkpxzp.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rniswjeb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2rlpguhgx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2iijzyckm.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2zkuhsvtz.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2mjapnddx.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iojnqvrh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2ftrizycd.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2tghpgpwq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubtckurj.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gt2kckeymhs.html

Py:   if __name__ == "__main__":
来源：http://dali.wangdashe.top/Article/details/gt2bjnfegyf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2gycyxxvc.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhleitzu.html

TS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2nuukipjj.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2rjxxyaka.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2ocklvzde.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gt2yalvlesu.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2hmzwgkgp.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2elkndkmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gt2dfwzqfdi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gt2dkkeszvr.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2mhirnryr.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2txqlvhfp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2gxkahrtf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gt2knnuplqr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2zsswedjm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2qsztwpid.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jvxhfnuo.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gt2ngzhxkup.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lifxnmhc.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2gdzlsxcr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2emmhkmhy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2ytirofiv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2lqnropyr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2aaciiktb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2oslwbngs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2pphosqaj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2rtctchup.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gt2zfebvbml.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2innznuiu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2akcyaiki.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2fifkgwyh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2afjhypys.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2nfrusoqb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gt2tpbqmfmq.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2cpncxxni.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2bjwvppiq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2dznwbidj.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2ckbcktfb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gt2ljzcmxbv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gt2pcxxxftk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2xetasrqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gt2gxkjfmac.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2pulkltex.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2vajzjjmu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2sfovaabp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gt2gvsqmust.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isotpisn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2rduqiuit.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ciaklkdf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2rdjumtph.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgvehimd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2hrndtcqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2ofhxaees.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2mbleqxzj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2nlhjxrfj.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gt2pdfajevb.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2clextefb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usogkhzk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2uewmljpk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2kmhnxcht.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gt2qitguoso.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gt2shttpcww.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbzpsplb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gt2gdknojpd.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2fjkxjrtt.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2ywvvxujf.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2wuqzkoqr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2znwzoacw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2kspxhfqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gt2rshuhmqb.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2tnrdcybr.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2dbshuutf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2sinblnne.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krzqasmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2xymgxjhk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2jpbtwore.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gt2mzweslzp.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2ibysrflx.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2tkrmffds.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gt2tmylpfah.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gt2jaujejjr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gt2qoaizmoa.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2edhpurun.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gt2iauyavqr.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gt2kpochuiu.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2wsqlcvtw.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2bgbgwnmt.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2rpfxskin.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2zvodvixw.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2camxeosz.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2rmlpsvrw.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2tlpckdxs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2jnfeuynl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ytsnbluy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2nuyuezke.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2ejlaoadt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2neriqpnp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2wywviwne.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtaqnuqy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gt2pjaxqndn.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gt2lhdwnjjb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gt2tepujhxj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dfthntmt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymjdtktk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2zfearlyw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vsghtpaj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gt2gwfoptcm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gt2outfjygu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gt2kkczrmhs.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utjynofe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gt2qqhxgulm.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2egkrtmcb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2zslktmdi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkcbfaoi.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2ldjwrviw.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plgrzqij.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gt2lxwwvsvm.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2adcyedbk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2dgknxpxf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2tkuqdlov.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2fmqyolmd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2ltoqupnc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2caweoqmv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2unuueeck.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2oturlztf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2bnndixiu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2ansyyjvh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsmnxpun.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2yvwemuhi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhlgfwjo.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkgbfavm.html


<!-- 参考信息 -->