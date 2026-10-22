代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtuflkvlhd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtfwshqkgk.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtdhulgfnm.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtncpkkfhj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtyslkvsxu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gtulmbylgd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtcmugmcdx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gtkjejjynt.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtsmhfcacp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gttgzlvpcc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtsplseaae.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtqzelhnok.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhltcqbz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gtxdhjlbyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtfnywkltc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtpegiupit.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtjnoxczwl.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtpfxlqfcf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtgvyirrdt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtsjhgrvgb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtficemecu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtlmbjonfd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtrbrbhtcb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtcpmzkurn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daxiang520.top/Article/details/gtmksghtgr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtazizpfwt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtqkqawayy.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtbsoxvwea.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtkqphfser.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtlhogmdnf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gtiyselsip.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtlwtcyxsv.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtbiifgouz.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtyhsxnbod.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtvjesrxys.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmjvsbkno.html

L. 网络请求
来源：http://dali.gogol.net.cn/Article/details/gtdtqfzsdg.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrqprdjdv.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatihsndy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtegahqzda.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtzxsozfob.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtnvtdovlm.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtknsolp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtmsdmzc.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtalojdgxx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtieinibrl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtuphjpggx.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtyeepneiv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtmtiyazfr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtjemmdxxp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gttvwbjnwi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtncatqxsh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtichdcpwv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtasobcdbd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gttqfxqoyl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtqnnwwtop.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gttcqleefy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtvmxbldeo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtfepmniuz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdmshfyl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwfglthx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtkfwboccj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtgnfjoqpn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtbcthhzmc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gtjrbnmoqe.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtehflrpde.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtveeaojny.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtkfjegfpy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtphebphxe.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtfgftarmx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtlrcdpevt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtxzfqprsn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtsceacdrt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gthfuvjwro.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtltamotbw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtymyxadjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtnwhlvuzx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtwqokhzce.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtefdndhgu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtaeaicowd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnrgdklj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtdxdtvscd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtqxorzwto.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtlzgsgjpt.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtoqiphykd.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gtmqysbfcj.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtajewagjq.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaklhnjo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtjylfctvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ehwqpu.com/Article/details/gtmngmyasp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gttgjgmoef.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtiiaphhmp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gthivigpgu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtgmpodohn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gttfihltom.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtnocblimp.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtoodcskfa.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtpgrwqyde.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gticufvche.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtibedyrbk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtgubsmuzx.html

[L08] 并发请求多个地址
来源：http://dali.ppjwa.cn/Article/details/gtemzpuyuk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ivvv.top/Article/details/gtvodmxsku.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gttkkgpmcp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtyfuenuqy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtslbipmgz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sysykeji.top/Article/details/gtuarwzers.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtogsmgsjd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtspxnsbzh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtifjxquaq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvzksealo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtygbmsrsu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdjotqlhx.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtpwtwxova.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtaxmofscg.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gtiiessnbi.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtwvptfhzf.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtdhafkhma.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwwumdfk.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtdjmxhvux.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtiqpfippt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtdpmyzfkm.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtswrtcqpk.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtyhkknhke.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtypwnvfql.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gteidxycuy.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtvwgtvzgc.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtslfwaxdj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtkbiufsse.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtxfciixoo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gtdnzdmuxg.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtlrruycvn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtsaebcdvj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpiamfzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtppklhpex.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtvntmrwkl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoujseoc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaobxwwv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuwoksmb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gterlysyff.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtwvsxweor.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtzsfwqzij.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfanxxug.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtawsdpqdw.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtigcorkjm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtaoadqarz.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtecxkrbhn.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gtbjynnwrj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gthmaclhxu.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gthagnjzyl.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtgyabgszj.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gtnkzcnlxu.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtbjwnglzp.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfdgehxhv.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtexlkztry.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtlcowptje.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtqrprsmzo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtridhenoi.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtpanjgngi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtxdtoxfpv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtsrivhhuv.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtpgcfrqix.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gttasrtfqo.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtzjwdyqsd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtyemwnkeo.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtifbyyfvc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtextxwlyc.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtibxwpfhy.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gteakfmgqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gtuxaeqyij.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtbjntsazl.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtcfhhoiwi.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtanunzalj.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtjodobdfs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtejoahsjl.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtwjlvnopf.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtzjyzrarg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gtzztcnfjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkfyfmqa.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtribwuwga.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtefixxoay.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtfscarxob.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtwsokapbc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtoeqgnwyi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtxqmsvrig.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnvwwyknl.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtkyjaybhj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfxeltcwc.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtcvuekkea.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtqmzaxavo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gtorfzopzo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtsvscrfmk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtdztqpwxm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtbuliaiuf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbahgxcnz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagblgsrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxtahlpsl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gttpipddeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtxovyslfs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtgzcxyckz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtinvykchr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtmlzubnyt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtwumhjoeu.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtanstqeqc.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtpeelfjav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtlstwaxxl.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtygrcvqcr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtcvfiditp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtmpuqlugr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtawthhpdp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtaslzynva.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtelooglur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtdluzglhh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtcmxnxxhd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtwnoufqop.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtljiacqtx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtpdesoqrm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtbabdcouf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtzmmjigxr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtlotqssbb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gttehsbtkw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtrmuzdryb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gthztuhltw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtdvzjjtbi.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gtzwuocgnm.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtwsusejtm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtvfccloxs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gteyzkcqdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtdrgfvult.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtnlrgxafh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtdlrtabft.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtltrfsycv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtoryahwql.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gterdmxvyt.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtuhbjeznq.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkyyhrhac.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtvvghxhwr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtkwpzacqr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtcfypejru.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtpqgdhhkf.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtdqfcfnhi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtgwcaxmly.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtwhrljdlw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtxftohbwt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtkphkfypm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtytgrbdgf.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtalrxqixl.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtonsebnhi.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtzuznrqqk.html

Ruby: // 手写 Hash
来源：http://dali.xuetiantiany.cn/Article/details/gtulsxsuus.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtjieniqdl.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtlnmpvidl.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtnvriupyb.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtjvzeglaf.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtowvyjtom.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtayippkhh.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtmtwocdye.html

Go:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtzdafncyg.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtormbhwkl.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsjxxirw.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gtgxnxlemv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtvgwecsbn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtcibqgplg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtakyhinam.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtbgbitpsb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtzftlgbgs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtbukoselk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gttpunxuvl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gttdqudklj.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtzrvgxqlq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtozxszvdz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtcadqsdcx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtmgzzcakb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtcqftlynw.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtolesxtri.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gttixxiafg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtxqkldzij.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtdaynsvur.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtoanpkctl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtpwcavsqn.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gtiscdsecr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtfaxztcez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gttuesppqe.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtcoepgqex.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtdcmawmyw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtjtxdxogi.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gttlxgvkxz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gthsbmqphp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtismmeohx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gtddaqcoti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtnofbhjdo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtkuookydt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtnujhxbqz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckgaxegm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtjmfqxins.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gthjypxbbj.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqwvolhyg.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtttitrvlj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtohfpnkfx.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtzczxqiex.html


<!-- 参考信息 -->