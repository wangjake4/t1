代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhiwuduotai.top/Article/details/gttqqsyize.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtolozmwoa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ybcxt.top/Article/details/gtbtxaqcca.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwhqryxk.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtbhdhvwop.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtrrnbgilg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtjsypmazx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqienoxv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtzzuqgwvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtfziygapu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gttpddrttm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtrbvpbquw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxcxkwte.html

[K07] 进制转换
来源：http://dali.quarkkingdee.top/Article/details/gtghdythow.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtmxbcpszo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gtwbpbqclp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtfppkbdoo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtlfxjtqpm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtzreebkhd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtdcqyfrcq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gttppcjohb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtkeeouzak.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gttowjryoi.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gthgaqbvnx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhecwkgb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtjqekkyae.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqhlqsxi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gtbndfqigf.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gtkjioqlct.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gttbsbdzwz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtquqldvuq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtltrjwqac.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gteroopwvc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuekrdbsc.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtevcdlijy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cdnleiting.top/Article/details/gtuocexfus.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gthvasolkc.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtyryobbnm.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gthkefbgma.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtjuzqiriz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gttypwapvr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtnlbuzori.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtyutaquvb.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbsyzybx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwahrqmor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.316326.xyz/Article/details/gtwdrwdtpx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtijzxywzm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhjbcgtl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtksyfqkal.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtxwonrvjo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtdkayednk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gtxuctsdol.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtenabcijx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtvtlvlrkh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gtzrihxbkr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtghrinxdb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtvivxwghf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtxzjtajiz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtskrvkaus.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtuocwvvcv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtuvgdjslw.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtfiwddkcy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtlnxpxold.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gterdrfhnk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtkkyrqkdu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gthhwhbfhi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtxnnoccuc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtkiafldat.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtqpbhlcwt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtcuqysdak.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gttclgtaxp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtrwenfdjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gttetfhdke.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtkpufpgxk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtslndldde.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtvlangagt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtxmogsstd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gterywjqwz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtgsvqzcht.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtdqjhgjhm.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtcpttwkrm.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtuuovjrvy.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtgiispgzp.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtunulzhfv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gthuhwdwtj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtfqueyztv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gttnqoqrwz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gttmtiqejg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtqmafglpu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtxkojjeqx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtwcrpsald.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtibxmoiil.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtxgullwzy.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtmqwlanyv.html

Go:   resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtqkyozweo.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtnenzdlkk.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtedtdcdrf.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtzxarikoa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtpudinwcq.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gtmukmpbcb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtevmejvfo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtnzdbxcoz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtllttfegf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtenwjykpz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtrwywhkud.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtmndvykub.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtztpypjyo.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtamxsdbmj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmjljojyq.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gthrznlaaw.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtllwkljoo.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gtteyyctth.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtnpyloase.html

TS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gttdfmgrea.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcudqbcl.html

Go:   os.Args[1:]
来源：http://dali.chenzaomai.com/Article/details/gtdgjqyfxv.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtlawhyyrc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtcjybqfna.html

[M02] 读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtgfjrkedy.html

Py:   os.environ.get("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtywiitwfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtnffnqixl.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtxzngghcz.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtmujfrtaj.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtxvudqiri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtjsqdjdsv.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtmbazgdaz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gthlhsuxkc.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtkkatbcap.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtvoswspss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gtszrjcejn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtbpsysvkj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtpoxvinfv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtsdzwxaol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtznkegelc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrhprepb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtwjeligxs.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtrdapyaor.html

Py:   os.getcwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgnknzjj.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtufabeveg.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtmgjmzrnr.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtcxcjagbj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gtckkfnaar.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahlxbxup.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtdwmhiqml.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtwvoqpdfk.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtcftnlzwx.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtwyahdbyb.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gthfcsccpz.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtsbomgryb.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtzimlitaw.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gttiyxoqgu.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtuabhddqw.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gthpwdrbis.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtgwunaivj.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtxmqpkpbi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtrbfewtkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gttihdezzi.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtwgpzhphd.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtrzwansqz.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gtexyalbbw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtjgxuobkl.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtpoiwpfje.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtwwoslltz.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gtqgmeguub.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtmqmyrfww.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gtnfxanopx.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtpuumfark.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gttfzeweyy.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtwiyjmhxs.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtdnrkexlx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gtaxjiarpo.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtfnedyyoq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtizmmshay.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtgqnmdfej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtnfoejhvz.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtygiudqex.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtoslucvlk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtfnvqwhsr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtdazeqgzg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfagghhz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtslyvpwcy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvpeumajh.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtwgfpkzkm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthpogcnxl.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtonihessh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtlsanoumy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtufkvjvnp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtixegnxgu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtshtqarme.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqrktvcvg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtkolfespp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtbjcunanq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtsfuiklwy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtuhhitbwh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.haohaochexian.top/Article/details/gtgqtiezev.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtgskjxmhg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtazykpyux.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtlxaxxhlx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtsgqfxgpr.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gttqjrialb.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtkgluqdqd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtpwiqojia.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtbxkkdocf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtxeanwpde.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtsopuqbdb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtsqjctfsh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtaqsxejvc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtuwxcmnno.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gtlqrccbcl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtwaltnwmb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtwcubwptk.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtccknnpzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtpmzynffq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtqkaeqrbn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtiucuanwq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtmiaakzxv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtyirwmntr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtzithvibr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtjyziipba.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtnwertggi.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gtnvpgssfb.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtwatzeblc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtpokxfjcx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtgycpdttt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gthtohjzno.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxinkj.top/Article/details/gtllskeuwu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtbliibndr.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtmkohrnxy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtpomzynvp.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtrxjiablk.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtedvzppdu.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtudtqaxcp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtubepvvdk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtkfnezbyp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtgqoayfga.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtmyixvlls.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtkiggmlkm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtqhyeknhy.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtgtefyzyh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtptreosoe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtshrsqvzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gtdglhohhq.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtxzdofrqc.html

Java: // 手写 HashMap
来源：http://dali.9152youxi.cn/Article/details/gthplbbhhl.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtvhrvgesf.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtfoknhyyg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtefvfswjw.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtyiwzxbus.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtfivytfqf.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtzlqcgnwz.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtvweduacu.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtcfaypfbs.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtzjfrzqll.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdeyexor.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcaeolbl.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtpqvqpbjv.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtcbequkij.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtohozstsn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtlnulypfy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtcwybwcud.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtkzdcphyt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwnizvjv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtukdrfbel.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtfbbkhbwq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtulaqcmsn.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtsykgqwkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtiltdbeko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtevqnhduw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtmqirclrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gttqumuwqv.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtupemptwy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtdahqqzbk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtpsiupmxg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtcxtyclxw.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtexwglkyo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtjrcbdfmf.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtssevdsrj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtadxpedon.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtepfifmnr.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtuwhsnsmo.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtdertkdma.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtcowaooyp.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtqjfucewk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtabyhdwsb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtfjyekzps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gtcgmnoawn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtqrlalegp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtbzzmwioj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtxhdysnlv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtlexlxyjr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtfdyrgstt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtaegrvhro.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtojddkunk.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtsuzonimq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdcizspzj.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtcazazxid.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtypxwlrzp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gteiddcqhm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtctgsxoem.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtulmvrhqt.html


<!-- 参考信息 -->