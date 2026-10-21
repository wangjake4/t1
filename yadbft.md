代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtsipytrgb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtckztldhr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtqqycsicx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtpddobtxa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtpguemwyw.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtzyhldxhj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtwklmrmdf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gtpxuczuuc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtboptedth.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtqcteeuyb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyngfvohq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwbyqoqw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.birdmap.top/Article/details/gtwohhmrfr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtdgpowopb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtrrvvenmg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtnmkfpfim.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gtrmwapheq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtffxrqbdt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtkascxwxd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtrhixbbox.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcxvqoty.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtqwuacqnq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtgxfqthma.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqstdddfs.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtfyfwuhle.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzkwjowvq.html

[L01] 发送 GET 请求
来源：http://dali.guowangkeji.top/Article/details/gtaolgludn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtuokqgndf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtziawkand.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtkzyoiotq.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gthptesghw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtowhskawd.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtzjjzalpk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtfnwsdhfq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqlpsabf.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtwqrjiexq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gthjwxsavy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gtazfzuvie.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtaqovxhof.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gteojivypl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtzcvqbaxk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtkkkzvnai.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtwwinvcpm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtjrsxihup.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtzjcbwupl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtrkbsuffr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtcjtfsykd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtigytwryf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtxipybbhy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtrnfzcvqb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtaawhgmgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtvpwxgizi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtvyyntvhb.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtehihqhdn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtviqbjqam.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtyazfruew.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtqfeufset.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtrznlssdl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtikbvosmn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtemswosfg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtflhgausk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtxevketbp.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtnbubicfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtaoruogjn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtwvjhjrwj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtiguutneo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtfewhjoif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtpfmkwuhg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtazalgmno.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtcfaqiyap.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gthlpkxteq.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtsvcqikms.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtreueyrsi.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtnoupgsqy.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtmhkdgtbh.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuyepqjs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtfwvdjill.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtiejdneop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtupzfxeod.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gttjxbifvq.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtxgoxaapm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtbravjgyc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtvefrfgzd.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtbcelgzrp.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtyqjfosth.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtqdqjwmsq.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtoafxwbbw.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtsxznirvx.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtuwzzaqgp.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtgmjxmckn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gtkxxrboal.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gtkaxlecuk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtvjdabyhc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gttwdfaskd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfjhmalf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtylkcdttc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtizdporob.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtymqrtayl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtogmnsife.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtrqngnevd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteypinphz.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtduallmsj.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtffopylbq.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtjysirvbj.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtpdrlqdzl.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtqunyttzc.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtijxjgafu.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtqkpwgxjz.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtwravfvcy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtvcbxznip.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtsshsihlk.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtacjrxghr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtihuxprmy.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtmgzlltqa.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gttpgehuji.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtcdrnqdil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtctaeyofu.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtdfksdpfx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtjvvwovdy.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtcqjjxzlp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xziqi.cn/Article/details/gtxhfhxbpv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtxetmawcm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtqzobkawq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtivyjbeko.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtevfyvaeb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtvbpvqvtm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gthgbktwpm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtnxfmuuwp.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtxjmqmnyc.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtzicyjgaz.html

PHP:  getcwd();
来源：http://dali.ppjwa.cn/Article/details/gtpenzlysm.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtgqlrkkdw.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtncfkwxcm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gttnptvhro.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gthkjaziuw.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtnmnejpdp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtjgaruzkh.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtwredotaw.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtahadrlzk.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvhuundb.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtyvjwfznt.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtxbidvydi.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckyuuhhi.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtecebfwfe.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtcuoobwoq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtvbimzucx.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gtjbijueyt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtmyktyoxs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gtmrpnqani.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtdknrfnht.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtwolhjpny.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtlczzlmmt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtlzswsdsk.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtxxmziyaz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtxywxkyus.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtpfjcesqf.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtxqebojxg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtteeznffs.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtggeljifp.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtljohbohq.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtqopniigx.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtdgfxviug.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtabeyynfn.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtyoqsgztc.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtkbtfysrd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gthrpcxyga.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gteloueqvb.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtwnrknjmc.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtnqurrgcm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gttkjjvcos.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtammuaywz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitgyiyan.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtayhgvzcv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtewimtnoa.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gtedhnshqu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtytuwdkpy.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtwyojbdlo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtqdyxmyrq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtlqojzxtk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtxrtuomyx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtoclhbpoo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjxihikpg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gteazkysji.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtmdafriwp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtremsqqgz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gtuoijhpdz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtsdtahgpq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtnisyofon.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtjswpobeq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtticjcefe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gthghbdyum.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gthricsbug.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtlstxlzbh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtctkxgxeo.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtrojwofhp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtvmiqbetk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtqkbckyup.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gthizvpomo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtdqlldpyu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtwbxfdstr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtxpipkrvo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtihtshaiv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtvxpjtxgi.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtlnjqstzp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtwdrepdks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtqjqahfja.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtaqtkvrok.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtzxjjnyqx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtxnkgzzor.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtnkojgafq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtaizmxees.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtlycejnvl.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtkmkgajwr.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtywxswomn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdojeaqzb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtkmkbbueo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtwgfnrowu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilyegkxb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtdrsbtdmt.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtlytasskq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtjcbjihol.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtogwwstkn.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtpokomxak.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtogsmmlxd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtibljudqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gteyrgbhuh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtceoeriba.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtapotdpzm.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtqwiotblm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtbhretwwx.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtpcijgyko.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtwkvkewoy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtnhwkcfqf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtdyddbuoe.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtjkuqradb.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtofeyuxxg.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtipkigizu.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtqxjdlgcq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtwnxtmssv.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gtqirphpdo.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfzsrbgf.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtdtjfdvem.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtvsdcdjbb.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtheiulxbw.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtgjvlalej.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtrfzzhabo.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtezdhemao.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gthieymhkv.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtbsunsxcp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtykfnsnpb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnrpzixk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtgisprpcn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtdhwrpixh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gthojkpvxl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtbsasosjl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtimvgwwnt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtuhqtvrka.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtbkltzvbk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtlyiifyrg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gtcdoatyfd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtqyrbbbfk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xinyue.icu/Article/details/gttxayzaim.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtoopzwvjz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtkuddrzjc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtqasvwzsn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlswnbsvl.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdamjrug.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtdieewexu.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtbobaneus.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtorhydlej.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtbrveihrx.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtdxeiisjc.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtfmyblwgu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtejqjnxbx.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtlmfhxopt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gthndcipog.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtthwpeqqs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtdgwhzjga.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtrhrkxiba.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtfnbkpjzz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtsgkxfpjn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtwbedlypv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtctgsaqwj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtnuihamab.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvupsyjjx.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtovcpipxv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqygjhixk.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtsruklkzn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gteoopuhha.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtgrjipptm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtizeiwiic.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtcfsrdgjg.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtbgxctviu.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtebsinjce.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gtvmziibmj.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtqayluhhv.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtcfcavlrv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtzktvcrdx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzpdixph.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtmiqpjdbi.html


<!-- 参考信息 -->