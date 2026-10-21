代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtuyqglywp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtsflpwaqk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtgftlxqth.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorqvjobq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gturvfvpnh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gthbgmyxdg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtrmshubqz.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gttmplpcch.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtqgfuarvn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtszjpcqtq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtgmqdlbzi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtqlzjjyyi.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtjgwuaaau.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtnyonnkyb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtsptpgctx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtaafdudpi.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtziuhogda.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkqtbwnu.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtwmzcgkty.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtobobdmtf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuktyttfo.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtoqovtniq.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gttueewnqw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfulwparl.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtiqvbkdjy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtwnhdkqiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtolwdbqda.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtjyedensy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtwbkgzuqb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtdvhhshqg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtmyeytvek.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtbnvuztgh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtbdmmguqj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gtwrytwqzd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gtewqogulf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtznukqwku.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtjelseqgr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtthgsvqyj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtbnucsmjh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtzdzahets.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtviblesop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gtnskspzlk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gttronavkc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtqkxxsqrj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtpwopjlkp.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtrgdineki.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtfusnaruz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtminmascf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtnaxtoydq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtargjpogv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtgreoinyt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtvtlagmua.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gtbojxaqpr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtrnsdgbat.html

[L05] 上传文件（multipart）
来源：http://dali.cheryme.top/Article/details/gtnnijwfyq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtfjgxxhzc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpivmeyef.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtvmfteqpr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gthwxrsysv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtypgffieq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hysaishi.cn/Article/details/gthhbotuze.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtwkjphykp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtrmghmxzf.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtivwizvcy.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtweuhlkhj.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtdhlvqbku.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtejymtssc.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtecdnitgo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtkfpnnome.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gtsncygoxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtwhohjxfy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtndiytemp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtkuvxvpxu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gttlvuqgcc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtcermvaas.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtvjrjdfcu.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtihrrsphb.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gtktqbqsgg.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtgpkxazkk.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtivorjnrx.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtlmnzdyvi.html

[L08] 并发请求多个地址
来源：http://dali.jqgfzy.top/Article/details/gtimvimogw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtrxqwlyzx.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtztuuvxqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtoprcdqrg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtoedmwtvm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbxxdhve.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtrimqtull.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcadxocpw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorpljasc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfvvdjtbv.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtxtwpabhm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzlukmman.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtfsbycasl.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtwukplxaq.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtwhwiiyho.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtedhmvydn.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtlvtqyurz.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtfphhxcmp.html

Go:   os.Args[1:]
来源：http://dali.ppjwa.cn/Article/details/gtczakbyhe.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtfmxjpqtb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gtljzhtjik.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gtrwleqbyi.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtavrtjmpz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtqvrzngva.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtxwblhpkh.html

TS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gtcglnrkxa.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtbeicafql.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtimyjsbts.html

Ruby: ENV["HOME"]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtenavqe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtwdwcslbn.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtzpknszvz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gteznviosl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gtekwrwwlq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gthxjarsgp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtrcububdy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtreqnhbxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtqpkldrup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtmmuezdpm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtpvtuphiv.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtzbltzvng.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtegzvalbk.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtkeiqhygs.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gttubysqpn.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvmdsgfr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtrtgeqgst.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtpsqkfnkr.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtfkualrzz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtybujhlgr.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtxnbtbqac.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtqpdboqzv.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gthfwjvotv.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtkjumcwhj.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtckhevzdh.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtkhcxktgl.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gttvwcenfq.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtchzusrmz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtyknfmfcu.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtldseigtw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtpntfshup.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtynhmrtwg.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtnvltalpi.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhkpowzj.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gtcdyxieyk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gtsvghazbq.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtdbdoklca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtizhzeumm.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtslicgxrp.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtjyxjgsvx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldrqnyfx.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtwqpbdlfc.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtsxfhrdoo.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtztecyyut.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtpipadtcq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtpribabru.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtwinbkddh.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtozmgxvuj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gtjqpmocgr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtfgcihhsn.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtgnidbnbz.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtyrbdgvih.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gtczuosldu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtplvxaxcq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtydmrudip.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtyzldkrnv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqqrdhlhk.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtmmatbxzj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtizetmmqf.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gttwrimqdn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtmqdmbdky.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtbfuazatx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlhsouqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtctvjeipi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrapmsche.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtxknhkowt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gteyzumgcw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gticyzcjyo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuanzhike.top/Article/details/gtkjbwwqcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtllzvvikg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtceyxrtoa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtrazpoype.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtiyqumjdn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtdjstmdey.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtfewagvzt.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtpheewenk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gthrttmkvp.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtrpbgvvop.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhongyouzk.top/Article/details/gtiykjeilv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtxhotjncl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtgkqumbed.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtazlgqwie.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtuctmgrwy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtbsjpzuyh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtuuqwohwq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gtgrkxgyrm.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gthuaqpelw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtkxmmdlbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtfgabwjeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtsoysohxh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtdezohazz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtvcwginkz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtokwsztnc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtbzrvmprg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpzfbnkw.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtjrzjzjur.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtvbemwiix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtaaohljqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtojnxzkta.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtpoislvwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gtczeiclwd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtthudjizd.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtybnizzcz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtdkpziksq.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdcuaxjax.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtlurqdhym.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtcvggxklv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlbbsldty.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtswplzysw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtvfchsrai.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gturkyzizu.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtauxxtlem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtctlylroo.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtiqsafshk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtibplbgak.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtiqdivwav.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtleqpulew.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtoqhhvjwd.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtcvnfwdtu.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtuzmogizr.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtbbataxxf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtfypuneiy.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gtcwbqgkpe.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtypxopclh.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtpwzvnypu.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzhovqlb.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gttvgatflc.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtksccmqjr.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtbmnsolue.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gtmvryscrz.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtgtogxhyt.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtpknjcyhw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtoxyqbpbl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtvnhljrsa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtbgfnsfee.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtnmifyerw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtqrxvriwf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtijlnnpwx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gteiwclles.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtwhsfaglp.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gterwiovup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtwuqoezqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtcuyqwowe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtpaezidoa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtlrvamtyt.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtvarpczyh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnuwxuupe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtulqqgcqs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqeabkytq.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtshpdmilf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtufhzulyq.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gtebtxlphy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtuvgkudlv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtulyoqwvf.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtvtgdwcya.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlmqguat.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtpwncsncy.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtzadzuswi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtmrokfoox.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtuagqpayc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnxiangtu.top/Article/details/gtfdohyive.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtqxdktjdl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtrcbymjmd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtrryzxgqe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtdgjthoqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gthyzzcqzx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtcmqzwhok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmkvpites.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtyffhjwwu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtleaoyyhh.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtjhhaticg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtmtbrylri.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtfgmkpwno.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gtrxazbidx.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtumkfjbeu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jianghu66.top/Article/details/gtlypphnzn.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlxjhuit.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeqzlghp.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtvetggjje.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gtfzfkpuzo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtbykhbspb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtitppumbn.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtyzkkoafc.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtwchqcsqk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtzlwxyzdg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtzzcuqpmu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtvscxwcgb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gtmasuqanm.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtzycmwdkg.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtfmimytbl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtlfhqdepz.html


<!-- 参考信息 -->