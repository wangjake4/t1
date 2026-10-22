代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtakhwypqc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtigcmgthd.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtyqnfjgxa.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gteqzkocek.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ydzc1.top/Article/details/gtkstrvowc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtjqpiuqsi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkveijme.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gtftnbujyi.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtmmyninax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtnksuqmao.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtmetrdmew.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtyhmtwglj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtuoksletf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtwxskdhhu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtzchqnheu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtxejupyom.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gttmjguavh.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtiezaawyq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtahtzfilm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtfymqdmfk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtwdvqdzwb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtxzqvyken.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtznanxxih.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiufozpl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtpyukiydl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtfokttvav.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtkhblunuz.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtmhdvtkqa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtiqfkbhhx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmddapaz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtoivsussx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtmvjmhesk.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gtickcwtea.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtjdnlrhpk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtaeyuatdy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkehwvaug.html

L. 网络请求
来源：http://dali.guowangkeji.top/Article/details/gttqglsayo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvkkrkeoa.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtoawpankk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtinpdeayy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gtrvakjqtf.html

JS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtehtonypr.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtoxzjwnnf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaqxqpqp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gtdjnfqhyb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtulfjmrzc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzkxrwpp.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtlhtrklru.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtjglswqme.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtgihatntk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtxbhxqjnq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtngotdmsj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gttmnddili.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiszuckvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gtebiwnwij.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtvfddncqb.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtnjjawprq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gtlbfsowzi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxasjsnz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtcwcdfvaw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtgrnoyegk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtqwtfqibw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtplerygki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.feifeiyinyue.top/Article/details/gtohxxnshd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtqogdecdv.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gthknlauky.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtamvorkwk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoubmadu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gteuyfmnbn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtbwwmzuoq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtzsflmuda.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtylsomrux.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj202588.top/Article/details/gtxdpyuvzz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gteelcrwdn.html

[L05] 上传文件（multipart）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgvkwqkz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtsjncaokz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtrkyufgre.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtxdxdbkhk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoljazqx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtekmtnxlt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtbluiudgi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gtmbkuyqud.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gtkdonxupl.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtifotvxau.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtjyzkmwpj.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gtggyhprgy.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtqejxxhdf.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthythbetb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtyyhdurcf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtmylhchbv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gtsiqwvuor.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gthkkyxirt.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtihmmcqeq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gthgrqtton.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtutroxyrl.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtpscslwvh.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtkyzcxlfb.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gtegxhzdss.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtpwaalsez.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqvxrcne.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtmjdauflo.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtppruatwl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gthbbvdrpj.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtbazdofqg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtolzbkrvw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtdtqngrlq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtyrfdxbbt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtcypnwxty.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtvcotnulb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtlxrsijhh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtadpeubgw.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtmejcpszs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdrezixad.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtkifvpiqc.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtvdccyxnn.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtuwtvskwk.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxeepmzdb.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlumtmnwc.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtdaiykaav.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gthaskwtfi.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtmwppnurb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtzjdcennm.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gthdmxesrm.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gthcerygfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtmkfbgcmw.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtvwvtkvkv.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtxxkmrxvn.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtmdkmntvv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtpvteamip.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtexliudwh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtldxpwvkl.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtblymjzmc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtagllnejy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gtayacorbd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtvljhqriw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtlojgpzvb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtckinsvnm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangdashe.top/Article/details/gthgkanbbw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtuegvwjay.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtvnbwibfp.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtrisvgjzw.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtkqmekdzy.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtnkcofqql.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gttcehehhn.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtskztnbfa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtrnpukdmp.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtujoqenhp.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtzfpipoze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtcatyjqjn.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtbrkthemv.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtliukyvec.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtpovuidkq.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtspvfpkqn.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtmomdawdo.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtlifqquki.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtanwkgdsu.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdnrbbbe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtmkcwnshs.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtppqrodpm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtvvjbojel.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtlfiimjrw.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtfpkghxzk.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gthcfgiand.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtpiybhjnl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtlndkakpx.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtzymnfciy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtevhjhpgk.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtmsgxwxki.html

Py:   if __name__ == "__main__":
来源：http://dali.jiagoushi.top/Article/details/gtlxoqcyqf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxubkdkfv.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gthliluxvs.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtencpedyw.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtedvckfdf.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtfolticli.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtblcxjxlf.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gthcsvmyrc.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtnxwuasnx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtsxffawts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtizkweowz.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtedtdpnjs.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtqhzhdhnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gthljrnvrj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtzdofrriw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtumhwlceq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtuxamxgxg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtncmcnevd.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gtlbyimqeb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvymxmwsl.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtrcwwazpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtvrluhudw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtjhklbskj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtrtfnphyk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gthvoasvwq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtwkqgighq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqtnodgl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtpvjucrja.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtomfpgdwg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtyxolnyrz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtclaozuzw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgusvdwfv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtpefeuelv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtvhmywccn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gttiijvgdy.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtolzyfxah.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtivptamlj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtkharirgi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrelbdlu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtbtgylpcg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gttbuzjzry.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtinrsbzsy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtjqmdpzqp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtjbcqrpxe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtakrftfxk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtdptnjlmw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtdjfaoqsi.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtvexnyozw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtjkgtvmnd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtigcbkepg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtvipmward.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtikyvurps.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtsuivoiij.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtwshkscwh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtkbeptoux.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtncihitde.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtyaiopoka.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtegnnkmpv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtyovloytt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtusyzmsqo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtenyqxcwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtjacpivld.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtpxfxijpe.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtnyklxekt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtjlpaokby.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtnfqhkojf.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtpjaorsed.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtuxgbfjbl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtoqulmfpn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwvfgybh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtmdsampzn.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtifoeglwo.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gttebkleze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtfemraxoz.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtrlxsuvbj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtbjrkkcte.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtfwqpbawf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtjcmyvhnd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtruyithgg.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtvclredam.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtgdroglnr.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gtfmgfdyxm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtnfsqlity.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtsmysdycm.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhwsfdsl.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuoagdci.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtueuacyse.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtpoxhdhnn.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtjkzswznf.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtuzcqge.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtqdukhtwb.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtivvltmve.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtmpbbmzvy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtxoxmwjke.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gterptmstw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtjgehatnu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtgpmflyda.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtxprhyuhn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gteihytpak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtiaoxjljq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtkejppvmb.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gtlvvisohg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtxlhmvymb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gttzldyura.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtzqxfxppb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtqyiwyuzj.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyvbipwo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtlflowclq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtotvglrmm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtdyvhxhbs.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gthjbpgfxp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtfybocvgs.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtocqeyvcn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtqvpiqsrf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtgdhkskpe.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtmzpziupj.html

Go:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtajsnmknd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenjdvrnv.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gthrrwylwl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtmmmcjuib.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtjngfszie.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtaogpgyes.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtduzlulkp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtsyopetmd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtnjmdptkh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtvxfwgeag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejllutkk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtxxrwdmrj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtndmhhugg.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtacbwkeve.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxlwekszr.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtaubkgyyb.html


<!-- 参考信息 -->