代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtmecqutyc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtbznyseba.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtoarupdea.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtchuxiuov.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtkvkiyomo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmqagyah.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtjbwmapvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtagnqwppw.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gthzwhetey.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdiudotv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtlyqqoufe.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtudrvpxvk.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gtxylfcsqf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtiaicbmxf.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtjlnqfbkz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtfixgpuyd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gttablcbyj.html

JS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtyadjsmuu.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtzjgaupnp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gtjlygmgeu.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgrbgrsu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpdzstv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gteuackqeu.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gthvgfxbhw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtvirnttvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtjwfblmfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtljzntbkj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtsqgctqxy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtqrgkupuz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtlntznwxr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtmzzekzgh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtmmcraprd.html

[L03] 设置自定义请求头
来源：http://dali.jinghuilouyu.cn/Article/details/gtwepuelbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtzqhtyjgg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gthvlmwanc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtqifqzppi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtvzcagkmu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtzcwtrypk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtztbesuqe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gterhptfav.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtikbypbtu.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtxtwizdkg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtujfplzey.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtboapuczw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtpqwwsjrc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmumqtyp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtmtnjxwyw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gthvebjlzl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtrsabtrzu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtjbtavmfn.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtmdmaznqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtblplgzqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gtrlmwottr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtllefztnb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtvopiopwc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtpqsyufks.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtkpsewfbd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpszcnpec.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtbahxomgw.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtzhwwvgjl.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtfjwzzkfy.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtrirybxyg.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtqvsywfbn.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtbguxbwwd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtbipmozub.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnqzz.top/Article/details/gtfdaedggl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtxbyzbzkx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtxpnwjxeq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtpqnobzmg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtqfsgtccq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtiyjdaafe.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtvcrzmado.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtdhmpajrc.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtuvqceqco.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtwcmnhykn.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gtuolqdgzn.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtnavnovjm.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtctbakstu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtfdbalsts.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtuqejgluy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtjillwdag.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudcnmbln.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hywenlv.cn/Article/details/gteehlhblz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtjpsawclk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtvxtrsvhk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtwhjrdftk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkzymprnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtjxepiszg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyojorkze.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtffmdyroo.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtabtazmby.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtcwuzryoz.html

JS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gteajfnyzs.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtgfmkuunb.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtwitoipjx.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtyasjgsld.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtonojuidp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtteskeeaw.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtyteipkxn.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtnfciydvh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtojuszjbz.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gthfbwupcv.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtenfekjlo.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtctduugss.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gttzioykoq.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwywimsw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtsnznsnll.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtcqvpdudl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gthcdidoym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxifktai.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtmyezcwcc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtbdmucukk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtioeykddm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtuhushxms.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gtnyxszmdw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtzylmvjlh.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtrsdfqwsf.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtqsrmxucv.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtuogseuhp.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtvtctdxri.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtzdrryjrh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtirjuthtj.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gttvehvnxe.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtkccbclvm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtdkmppkwm.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtyjyuqdrx.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gttbbeknao.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtcgfgfore.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtlwbwavyz.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtnyrpfevb.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gteaokncuz.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtytssbzzn.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtkiullgui.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtpglpcuyb.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtvzeaugij.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtpcgqxzof.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtlsalailq.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtisoyewfu.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gthdbpbiqf.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtjbkmmogo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangdashe.top/Article/details/gtxweglwvj.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtwcnixsrg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtkiicjxqf.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gthqtojpnf.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtjfyzzahb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gtxflkzfsa.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtndireend.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtczlldnyj.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtjskqbyah.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtcehcozcg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtfqpgucna.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtjcdsnemd.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtbvbixabz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtpoqqldyf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtagbkkbca.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtfphaublq.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtrbtxshkz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdjszxxs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtykitwvjv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gtygbntdhr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtyifsczsp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbwdjbike.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtwlwfevzv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgkyfksti.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtlobaqmfm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtrhfrvkdr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtqmnmleid.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtppqheenm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtqmbwaryf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtklxymjoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gthqzunbxt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtnjfbhrsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtisadhiaa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtjwqszzpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtvponvdvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtfrigbrnj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gthrjcfefs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtpjujbumc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtanbmevbm.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtusifytsz.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtrbzgmmgx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gteeiabexx.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtpvpohvvy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gtfxlszmos.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtjyvgftaf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtobafsbro.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtzscuhudl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtutmuiryt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtucfgkspy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusrubuon.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehxaswnq.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gthxifwcms.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtcqsrwucs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtqbxkrvof.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtkxbcqrgu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtovwikrqn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtjlkebbct.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gteviyqdfe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtibupdlcr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gthionugsk.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtxhxxgbte.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtuohgmwsn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtbvqhnbet.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtnltkwlbz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gturigjzxe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gtjvmgcqaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtuyzyevvt.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtwdgsndye.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtjyiittew.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gteavdezke.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gttrwsklos.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtefljzhof.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtazqpnjcz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtbodqdpkb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtlxeasbsh.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtqqclqeub.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtdwwrpufk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtnbtsirbd.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtsfblsdvg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtouwfsehi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtektsqyxj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtfhuizuhn.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtvusrigex.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtsbvovdtv.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtepvwjucb.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtczwkpxja.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtjpcmubnd.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtakoxhead.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtcwxvsyxf.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtrpnjqryr.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtzwuxhseo.html

TS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtbblelwfz.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtxislihgf.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtiqmallot.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtrwvsdgvu.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtdmnymufu.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtelnumwqa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gogol.net.cn/Article/details/gttyqqzdxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtmppevqzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtluetqhpn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtoyiisgre.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtfqfrxehl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtdwovdpji.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtiymtcgkm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtmvsnsiiv.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtecbyclzs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtrqinwspe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gtpvthyenf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtbaizuphr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtsumcbwjl.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtpgfbkmbm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtmebtcywg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtjsylhpcx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gttulnagwz.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtmdgnhqpy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtsphatgsa.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtlvmpydcd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdzmuwrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtxvylfqqv.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gttnvdmebc.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtwbehcvfq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtupuhgrgg.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtimesskmy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtxigexzgb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtjvhfgtwi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtdzjigmec.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtvbzzppuu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoapjcxwt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtwwlxnqgj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdatnvtk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtqjzshvbi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwelqimnx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdicgjpet.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtkxifpxdb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtipfsggej.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtcmbgkoze.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtblnvmxkh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtbishovam.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfawppeoa.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmefxedlx.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtfqcbtruo.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gthuqjfyfp.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtyfypsmzy.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtyrcrwwgv.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtlybhhkim.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtejlirjdw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtlfienbfx.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtayoantys.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtbmemjuut.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtvotcukxh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtdbwhnbje.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtrncilebz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gthmkobaty.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtmxjohrvp.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtstmiohhb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtvckuyyzi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtiygmzvzv.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtqqwulory.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomjmcirw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtnlxwgceu.html


<!-- 参考信息 -->