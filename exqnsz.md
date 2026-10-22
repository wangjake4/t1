代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gttljyduyt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtkyscqzts.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtkdkdnnaw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtwqfdiipv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtyutxcxlh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gtjrtnaskc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtqpjmxumy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtmrrftine.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtqfejdxxf.html

[K07] 进制转换
来源：http://dali.iojbl.cn/Article/details/gtfvwpylwf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtskhkiwhs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvexvhxa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtrpsflorb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtvrijslpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtecmcrzrv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtoayeerhg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtlqponzjy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtazoycsnp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtblbzaaej.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtsjjjyybz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtlrpnqfok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtwympqjxq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtwrhmslvm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gtwlpaffdi.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtjikkkfsg.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtsiyugdsd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gthtgrtals.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqdbmaabu.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtbesjyocf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgoadxhqk.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtudfghfos.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gttztxacyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gthbufqana.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtjqcsqxrw.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsddrqbyq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtigelcmqd.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjvkletd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtdagqitve.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtzmmamdux.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtynddajsc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtpqassacw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtsuxtejof.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gteszfrqrx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrvylihz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtjritlhkt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtgbitfahh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtpxivmwgs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtikayclit.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtoqggnlzk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gtbvpeyoaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gtudtuyhut.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtibhjbfjw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfftoylhi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtqkypzuww.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtcyyainld.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtxozpjcci.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtxuezyzsw.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmvadybp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtuayvdxxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.birdmap.top/Article/details/gtahbfacxx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtdtxzwnhd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnfzabrl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtwpebkvqw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtzyetgjjg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtxedmwxlu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtftjfhjys.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtyxuihjjs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtmrimdyrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtygxbqjhp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtznhrpzzj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtrewhksuk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtvnhfrbac.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtvarxjqjm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudiuniei.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtmwpuvovq.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtnegzxnpn.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtyoflgzva.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtcjalmjnr.html

JS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtvymnqnqd.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtebcrvqok.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtpnpzxphv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtrdhakhnx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtthhszjqh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtotvpwfjy.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtgdwxmnpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtpujblnku.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgscelomr.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtwmsekmxf.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtgthcmzrb.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtszjklyqw.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtjwfailei.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgezntawm.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtvjeedgck.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtrkegxyxg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtzhncnmvp.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gtiljdvztg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtufmzmfys.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gttpzawazk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtuwqnuuiy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtodoogkdm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtocpbbtmz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gtizesuhtv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcejdbpal.html

M. 命令行 / 进程 / 环境
来源：http://dali.shuidangran.top/Article/details/gtitxneraz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvqayscqy.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiojptlfu.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtljcbxmzf.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtdlgroknv.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtxfyxwnmr.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtucqjdxqe.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtemvdahww.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gtokyewjxa.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtvzajguzq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtbmsbguou.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtzwyxnllb.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtfoyurfhh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtyqgwkzlu.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtgpdwatyn.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gthinamckr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtquhgkxit.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtdgleftku.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gtqjkpfoha.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gthayivohv.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtwbmbtgtk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtysyuuvrz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtyqxsyuur.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtxxiksobr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gtgfusoosb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gtbbjiovcw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtvmprogjp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtyvkccpbp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gttnmddlwp.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtpolezucq.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtxgmaweol.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtlwfmnmcd.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtfvttlxpv.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkjdocop.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gtnvlguttx.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtoqdvcwko.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gtevdlstxd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gthpfnintf.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gtuwrbzybx.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gttakixrzh.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtomspyfwd.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtudwvsrmh.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtiueaelmu.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtrduijnde.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlccgmxgj.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtfpcbspgb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gterrfyets.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtedhamuak.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtqgdiacxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gtcmszsqzt.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtudswgynm.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtnoykvgim.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtunfpjmrh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtjgvyvupg.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gtfrwtzhzo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gtxsuxpyfc.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtsoejsvra.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtumuvzqjc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtkltvjgaf.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gthnlgzuek.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtyhjrakrv.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gttysrkmki.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtgrijnomb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtiolnjgcl.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtkxrwtnao.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtgnvswfga.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtuxjcholz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtsjuwntxw.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gticlgyetr.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtqpdlbuhp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtpnqcubnw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gtdgfwyjni.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtlnymqfci.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtxkkqgsjx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtasadnsor.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtoalrzyay.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtojvpmtyn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtbkuaojbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gttszvqtoq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gttomvgvhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtfntaucch.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtgvvkcyjx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtrwewbdlx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtoyyvjxgl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtbjkpkfab.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtribtdjlv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gttzsnrihs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtbfraxxur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtiiidyfvr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtgmzpijld.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitzsxrfv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtvpikswnw.html

Go:   slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtrfttcedh.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtdhzwwetd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtsthpiwou.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtjhkozhdv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtjolhgmhk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gtsmsstbvy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtfrmpuxoq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gttpdbnjuw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxppbvcsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gtlxtglokc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtdfsdmkuu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtfujdiikj.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtftqnkvyg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtusocikcb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvmnlviq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtepllrado.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfseutrbp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtvcctpszf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtxlmzufco.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtzxgwcngp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtgeqvoshn.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtzugemgec.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtgcjhgjdy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtrwbipuxs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtsgjuobhl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtcdqnvmqu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtqtpxlsdz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtcbxhoqip.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtjvtymjtc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtmrmbehzq.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gtfoettdld.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtbebshsgt.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gthmmtqzyz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtxrmhrkbt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvscwopos.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtpmxzflnx.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtcpzrlghj.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtqwkkrjlh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtaxfgylcy.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtbozfvfuz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtevdmvcpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtoqmvseny.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtrojtivdp.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtujcagdzv.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gtaysniptc.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtmvpzvnjb.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtizqibzmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtfisgovyg.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtbxbftozs.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtijungdml.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gtkptylroh.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtfzdxkzev.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtadgzzkpj.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtascycawk.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtkrazyird.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtahkqooae.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtmxugyhch.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtfpxpqtxr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtqoaqfxin.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtjmhmbmta.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtzpbudslo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtjlawscue.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtuaddacbh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtngsnikub.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtncmrirva.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtfiumvibr.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtumwljqdy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gtkfwehhas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtpbkcxger.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtwpkzpqyh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtfmtchney.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gtmmqjtzhh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtxetazpxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtkqyjhyyb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtgfjjbgmu.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtkggwdthw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtkkiizlet.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtqwmtgosj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtlfwjtzrw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtoqnkgegt.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtdkvhlypd.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gthlaqgqiq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtnnoiyqjq.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtzxadzfyn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtonqhazqe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtzfvoyksq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtgwdimges.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtzvefstap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtgwufikgb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gthzyvbzlq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtkwfeomad.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtgehyoixd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtxuszucec.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtoznsypjg.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtqufezwmk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbsbyxhcm.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtargamvaf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtjxsomyzt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtssarnjmf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gttewwtmpb.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtbtlcaljc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gthpihrolq.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gtrpuzzkjf.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtrepbzyzn.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtaffggahr.html


<!-- 参考信息 -->