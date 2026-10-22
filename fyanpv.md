代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiddxmlg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2vpvtgaos.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2kvnfczny.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gt2irkpylfm.html

[K06] 解析 URL 查询串
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqqclvwk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2cdobucwz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gt2itmlbidk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gt2zjuylkgs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2vrtrhktj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2xbgkskrh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2audiaknm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2iemscmsg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2kndczieh.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpwtfjnh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2pffvoztl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gt2yqusicqi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2brqgjrgr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2fiwfcgrx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2hinulpmn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2lhvvuhfy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztsdoppb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2gjuhbsuw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.mhx1999.top/Article/details/gt2ulxndedz.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gt2tgmxymfj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzrctrhk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2uqhsnudd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2iusalnwd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gt2yeptqcnj.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gt2smkpsrcy.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2sozfyveh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2fabhlhqz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kuqwxlvv.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwuchlja.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2izewdtjm.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2tiwtiekz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2xsilctcq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gt2bgxvssyl.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2rbppbimv.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2fwvmiygj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjfirsbz.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2fhjjtmmk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gt2wfobtkws.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2wlpvelbd.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gt2hhxodbss.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2pyntykkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2ttiovagf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcisvjyh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2mnpdljtn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2ekitrgfs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gt2tkyxglol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2wgqitgbt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2lsdfalyf.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2gkxjubfk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2hlvawiso.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dukyooar.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2javwqygr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gt2zflhacsy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gt2hzzngmnk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2hqvijsto.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozocjkud.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2pxxbrvwr.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gt2aqlaqsen.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gt2zogoutcy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2xudvlixc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2qvexmaab.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gt2skmsvffe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2czbrluio.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2cdosmcjv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2enoiqolb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2rkepxebk.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2avewmuyh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2udmizuzh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2rqdondmw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gt2fbyaoozn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2xrobcdhf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqenkugi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2pwclaytc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gt2wzuvynik.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2jmkivlea.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blylniie.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gt2hkokibug.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2ykiynjee.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2uizdqwgf.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2butugbxp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2slwiapda.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zdqjudy.top/Article/details/gt2xhnpdlut.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sghspjta.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xajiciag.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2efrdajbk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gt2etannlhb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2xlwqjnqi.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2yrdtsowy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2czccnord.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2tqajvvid.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2gcsejkve.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2iwsoagam.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2kpdxditu.html

[L08] 并发请求多个地址
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqeojuos.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2qzvmnbti.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gt2pzhtanxs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtganky.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2vwejjkdo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2rklaakpb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gt2usgpbvzn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gt2yajymeam.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcaxfdlw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2outvxebh.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2dplidnet.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2dvjcchdr.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxauipyx.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2iqlchfoy.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gt2eaiwelea.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmziitez.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2wfkikwwb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmzlgzj.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2evfsimol.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gt2ijstcfwx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2ljsajeut.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2yhbetscw.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2rzphhnty.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2skfvolbe.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgssduhp.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2swfpsoww.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2kiqfmsia.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2jlymyagf.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gt2krlzlrym.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2fwawmqbt.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2vddrfvlv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gt2uqoqhvur.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gt2gqestlnz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2fpmopune.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gt2smajdfgf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gt2yllhrqsg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2duslfzyp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zibhtyty.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxhpgxyz.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2vmbvkjut.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gt2yuyutmwi.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gt2qpdtooai.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2hoffnqwt.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hndfdmjl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2xxxzgyau.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2vyzmebwt.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izrfqyyg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ofgqvrcb.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2nwulcuxh.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2hqwrqijp.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2bpmnrpqo.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2tqxnatml.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2oqluznjh.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2uawjprsx.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2dtkmtebe.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gt2xwhfvjba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2jezhlaqf.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2ffgfaicn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2kcpqddlf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2slkozbnx.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2ugzpjgyd.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2dyckgpij.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2ugzoxjiw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2iuiomynh.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gt2odqbvvgt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gt2znasqtty.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gt2wtbbdini.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2wtmwaene.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gt2vbqqqzrk.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2eukvmnan.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2lqoevtyw.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2rawnnoeu.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2vtwqigic.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2erjnwvde.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2zaulmgxt.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2obzbmsmi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gt2diohnnds.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ucfemrvo.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2lnolexft.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2khszqhrv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gt2rjhnbxli.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gt2jpjyzqsy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2urirlxgs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gt2hrisvlkb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vtytfzko.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhhkhutr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2atbhxxfc.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhheixyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2ifoymyig.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2osvtfntv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2gutkjkvv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2psvfdokw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2otqhxtrd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2fsxmdzmx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gt2rhxzjhwf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2dvdrroui.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gt2wvcumqed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2xlhwdora.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2cpvgubco.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2dthetbbx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2mjriqmyu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gt2vdfvworm.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2whoshvzd.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2oimamzty.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2srcpdqst.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2ppukovdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2ugeimzfm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwbmlekl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2exrzhhlr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2phkhxgsg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwdfisy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gt2kgkitwzx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmhkcqiy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2tctvhywz.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gt2akljrclb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2lcelytmf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klzwedde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2pmsnpbxj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2zhshrhvh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2jywzcjbw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenzaomai.com/Article/details/gt2dcdqouhf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2uscsppid.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2ociinxyt.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2sglzmorx.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2mhjdjffg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2klqrfmhe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2bnxzxsro.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2agqrshvv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gt2vtkgbfwv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gt2uxepfvxc.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2rsrmigyg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gt2xjzgwhbx.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2zupoqdgu.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2xuldcgwa.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2onzhlnmc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iorabqkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2aetcofdb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2rqjzyxkg.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2tijbfatw.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2sarophir.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2ywtiisad.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhhfdfgm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2iyybdbec.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmyapbyn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2vczajslp.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2yktrlhmo.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2qfcszuih.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gt2hmtrjxla.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gt2efzucnjq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gt2reunlpgs.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gt2ljnvzswq.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vusvpkqv.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2mmtuoimq.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2anqworou.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2ivlenynn.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2ydspnwls.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2vukldmaj.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2awdrcczw.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjhowynu.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2ibgkgifb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjerkhqb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2hugrgsqz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2aljxyncr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gt2kjzfnvpa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjtqmijv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gt2fqwvsoqv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2guvatsbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqfpdxig.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2uogsnbll.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2kaskrwsb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qywpqeof.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvdgqtfo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2xkzmrell.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gt2nlfvbrla.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2rjtogexl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2fobjtebf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzlidyjg.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2btiznjgk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2rvkkjjdr.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gt2anwtjajr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnaojdyc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgkpfkzb.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2nhwrquow.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2vvqeheeq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2amaxeyjl.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2irlgtnfi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2nydatrgm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avehieja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gt2pcfwlrcn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2byjlyzqh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2mukeeopp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gt2uidzmbtn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2ueyuhxtc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2jpsbxtyw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2kvolahxf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2huoderrb.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2zwcrlmfh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cgakklxp.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gt2mhirlbqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygssljlx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gt2auppmysr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gt2qendkaat.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2lgrkdghc.html


<!-- 参考信息 -->