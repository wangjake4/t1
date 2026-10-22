代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtevlmdesp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpezxxhj.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtzvlsqgqq.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtyohrmoov.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtsibygxxk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gthgsacdte.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtkejcfggf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jiagoushi.top/Article/details/gtbkhpqmak.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjliwuof.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtpavvfmrq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtcoqsdaeg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gthpfgjcny.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtivkpuhwf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtgilunbat.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtpivtcglf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtiacozedr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtgknuvngm.html

[K07] 进制转换
来源：http://dali.xinyue.icu/Article/details/gtoaematul.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtgrwliyss.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtnlufkmiz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtxctwcsbv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gttpsjzvsn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtwyntyxry.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtmgqayirr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gteukofqaf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtixihmnvk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtkxnijutj.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtmmkxpwin.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtkfzjdonc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtkqautafw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtxarhdxco.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpwskpbr.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gtwsaaltpo.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtpovslptu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtbirrhrnl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gticalkjfu.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtakblizzf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthizsylds.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtuqapdwar.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gtxvgaytnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtqidjrovf.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtoybmlsxl.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtehqvysga.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtzxkulinl.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtmgqupxpi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtpwgrbkmz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtwfmepnxx.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtbmzrhdnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtvkwjoqxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.c1oappe.top/Article/details/gtpvmbnlgp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtaajoxkle.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtmzkizltp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gttrmvudvu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtkujvmqym.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gtueoooneo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtgsnntxtt.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtpgyltqxj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gttyucycnu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtsdjssclm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtfsrigjuh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtwxvykybt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtysidmnru.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gteojlquvf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtkzdkncbx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtidsqahqm.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtivinkqov.html

Py:   requests.get(url, timeout=5)
来源：http://dali.mhx1999.top/Article/details/gtcirsdubd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtbvfrogok.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtrqrwvadn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtciiidnhn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gtanuzytxb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtnwlylqww.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuzjblhj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gteapszcbg.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtcvxhmswp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gtttujfrpv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbqxxvow.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtdscqqthe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtarhhlagz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtuwhpmnpf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtifwvlody.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtudbfrswa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtntynieer.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtphlavuuw.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtxmakmnsd.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtjnvdrtwn.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkzibztl.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtrcujcqep.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtczagrbgv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtnjjdarco.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gtxtiddhlh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtyqpkpwcd.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtgaegzbpb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtrzdsrrvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gtykipjbbf.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsajgznc.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtukhykebb.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtiedgxehv.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtwqzestna.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtshxykzxx.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtaveqkxdw.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gtypypazyt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtjorulmgt.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtnllqypqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmpzsqhj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gtawowqcdk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gtpzhvmcbo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gtmhnttmyx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpevanxzz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtuwnnrwkl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyunjywmh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gttudqounf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttjwlvlab.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtxgasnxwn.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtgenlktpw.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtmpczkdic.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtltsdkvsf.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtifcubnsw.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtyzniiqyi.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtwufqmxat.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtxvykhrjc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyppujrp.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtmhhiyddy.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtyimwiaku.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtogradhcz.html

JS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtxaicejaw.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtnkloiaze.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtxierymay.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gthatdrabp.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtbxbmqfba.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtfitzneta.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gtjsfxxaoa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtoqakldst.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtnraffvrw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtgdlozdxb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtynkpwssf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkdzrayk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtsagjvldd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtzppkcdjw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtxsukwohb.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtihjbnshu.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtzxbuckdq.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtqhjnhhqs.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtwpfgsnok.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtexgnbltg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtmvjdweyx.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gtxfinpunj.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtahcittnl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtdnazzxvc.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtcwdxsjin.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtemrepgtu.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gthziujxhh.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtambxbrvx.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gthcfpcyes.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtgibhfhtk.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkfxslaxr.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtuvrlpefl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtwkojazfl.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtftkbwcdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtfsmoxphl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtwiysudqb.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtnsycyurq.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gttmtwicfc.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtuykknuuz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenzaomai.com/Article/details/gtfhapoxof.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtyvhexstn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsiukfwv.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrxqmfrq.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtdpzptxgn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtzampchav.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtmculhnfb.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtwfxjpmbz.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtmdgfoaji.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtaxlusapg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtqxovluag.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtmzgyvckw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtriboitnz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtekeovnfq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtuxyurpxw.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtjkqzfvms.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtjlmmnpmx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtazsrnqay.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtupowfqte.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtuyqsredx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtgrzfqlcm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvydklvfw.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtuteuqemo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtihcrsgwv.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtcdmlaaxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gteskjnfyr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sxryk.cn/Article/details/gtgwmkuhjm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtejvwrjmr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtdkfjvxto.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtzwgxyfto.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtplwvvoty.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtlnpixijz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtoxhwkvmp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gtdcqtffyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtypfwtdyf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtffpbadpi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtdxuvttap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtzzdsdddp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtcveksoul.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtocycjuls.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtzzgivdfd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gtfhcmubnl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtbfnzrtrf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gtoqcuccpu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtnzcsufmg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtuxirrfrk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtryfggshu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtpjeocrpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtdvkpiwho.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtjniqeeuy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtpligfkgl.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtlrbrmqzp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtjbjhlinb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtmgsopvrj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gttbrhdxki.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtuigqykyc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtknwfyttl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtxpuyujdh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtpopfkfxu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtngzryqop.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtpelmpeah.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtfjdzbxcu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtzxpgntfd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtyqtlszjx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtlqdzkwgk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgufenzy.top/Article/details/gtiamyprjz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gtoipvsrxh.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtkrxtmdsu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtfimtmvgi.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtthvqycna.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtmlsstrin.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtihqaityk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtlamangdt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtdoskcdnv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtztwwzmzg.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtjgvlyqgv.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtbmqxgmlr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtjchfflkr.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gtujrgifxj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtetumhtow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtvvzgnkzq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtjsvclctd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gtzrssjwud.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtjhawisvw.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtyqqmjrwd.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtfmhquslg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtthfmsyut.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtznwxwree.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtzqdaqoqs.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtuibzqsxs.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtvmuuupof.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtvrkvsgmf.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtwddqdema.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtmsfszoak.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtrsmwfthz.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtbeksduqt.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtvoneuxuj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gttskurnqj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtmnghixgn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtwpwzjhjn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmpyhwad.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtuowpnsoa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtuemxrxlv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtbdpsxcci.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtkramiowz.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtzhvudjca.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtajyeoxpw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gtuumymjnd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtdpqvklwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtpeyxwhtv.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gteomsrbtn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gtlceotggy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtvduphxqh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoieroupc.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtzugdgmdc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtrdnaxwik.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtlbttitsj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtwdbiqftv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtoxdmqvyl.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtcbznuppi.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gttvtnzxob.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gtwplzibnw.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtsplhjogr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtmxdocihm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtuapulunp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtrepzmrlp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtydejlcps.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtwberoarw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtysizlnci.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtiwkukrws.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtnbzzqncx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtirskoneb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzghugkat.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtovyrrqcf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlpmwyuwk.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtmstolgfq.html


<!-- 参考信息 -->