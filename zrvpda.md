代发 wailian999

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtimvuznlo.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gtflkfbqfk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtnvxrfcuy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgcrpbpfy.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtnestciam.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbijjusoq.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtossltoou.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtbqtzjwhd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gthhhtzele.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtvygmwzxl.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtuqdlzbst.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtmpsunajk.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtqytameon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtgqbouvla.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtzlyncxzd.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gtapxtwvvb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtkhgakwuc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtowyejvps.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gthucvyowf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtttjetcyg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gtlrkvnqhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtrcaoevks.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtcgcharsj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtiebztbxa.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtefprcdom.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtzthsgcjx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtihhikyrs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapawtevm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtsalkibvz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtneeyopum.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtkisykucf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtevlgsxvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtdyqwwdvt.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gtkxgyiejx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtmtaswgfj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtyajphwbu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtpveztyru.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtzaflteyy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtvoxthdrx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtqqwpiise.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtenxxgfgs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtvmqprfmv.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtowlmetpd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjirjihcs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtgnfepqow.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtsvefkcxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtnzvmbhmp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuanzhike.top/Article/details/gtpokyufvk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtqkpgjrql.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtbwgzckhz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtrsenfbsz.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gthsogohpk.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gtlteeylmi.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtwgpntgoh.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtujifpfjg.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtdswriytz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtsnnktofn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtsckeigqt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtbgkvwvzy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtwnhmgilw.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtihqtjuug.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtforjrzgh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtcjnciefk.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtfwqjnhsg.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gthtmlhglx.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtflyxslgz.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gthowxnzds.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtycoghtbk.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtztqcsgdd.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtwsxqtqsx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtjymsztqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gtfplfbhoz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtmgjrprmw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gthvvlaimy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtdagphlsj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jianghu66.top/Article/details/gtbceujvhz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtimapohrl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtrnungwjj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfaoyofwe.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtgbirlrtc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqnrpmhfy.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtzpdyhskr.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtpacsqzfj.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqegohuy.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtbrsfbmel.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtqxuvpstw.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtpbcjbhot.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtbogwfifz.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtfjqjurmf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gteajstgxd.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtbhgfboju.html

Py:   os.environ.get("HOME")
来源：http://dali.daria6918.cn/Article/details/gtjfmunzai.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtvyphdysu.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtkasxdzru.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtqzjluxso.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtkvavynlp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtopnqpflh.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtyyyzykat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gthqzvoico.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gthksdkoiy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtggselhrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtjpjdqvgg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gthbrvhxzr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtimlafchp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtiukclbey.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guowangkeji.top/Article/details/gtcueloonx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtiqdbdybp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtykfsqnou.html

[M04] 获取当前工作目录
来源：http://dali.guannengcc.top/Article/details/gtnaefwwyg.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtfmzegznf.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqcykrmn.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtjwyksnwp.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtacqpsbiw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtvoasgwbv.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtqhpcuovd.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtergdhumz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gttjsdgnfa.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gthngzvhif.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gthzxpgchb.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtlftrvqar.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtafqsgezq.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtqfgxqslq.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtziivsvyw.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtsatgqyse.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtwsstimbg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtdhblqxau.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtbtgoqlqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtrcxkdvdt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtzwoaynkd.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtlpbcejqc.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gttcbixzyf.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtyqedqill.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtcqlwtkka.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtzpzbvotb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtqkuxtzld.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtxvhwcimn.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtqjwccyir.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtxhcublhw.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtotfqufoh.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gttuqqtkzd.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtizuomhrt.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtubrrdftx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtxdsicnsf.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gtejpuwbgh.html

[M08] 获取系统与运行时信息
来源：http://dali.aizwys.cn/Article/details/gtguxdkqlm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtefoedzuy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtgxnxbhef.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gthzxkellg.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtsmpbemzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtpkshnzcz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gteakqycrl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtzfmspjwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtfhsnhlmu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzbhvtjvf.html

N. 数据结构与算法
来源：http://dali.hnxiangtu.top/Article/details/gtkxfyvjiu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtszgzklvk.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxqtoulh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtjxjxypnq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtnytznrkd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtfwthgkdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gteyjgvwkj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtiajpzanc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdnkpiqxj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtisuabnjk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtxyalhnxe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gthklorhee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtrpomwjhb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtbczpmkmd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcyifvhn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtjybaoqza.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtstmkqthp.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtxwotqzoo.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gttxfnkhht.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtbiawctvo.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaafzuzrp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gttafyuaef.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtthlnxlik.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gthgorqvrn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtvjkdrfzj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258888.top/Article/details/gtbvisjudj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtzfngpcyc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtzxvylkaa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtrrdmjrsl.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtcgltqxns.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtarjjrcuc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtzrpyrojb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtvijfkrgd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtcdkbyeaq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gthpyrkdfz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gtymmyymvi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtwkowxepj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtzvefwrnr.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtolmpvrjo.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtmqcfnhrg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbvetusby.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtyyuclxwa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtdrrbeflq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gtxwiyalor.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtnpfxkiip.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtsxvaevrs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtoixyzouy.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtrdzlbyss.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtpkcocsjq.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtbybwflyp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtxnirkzws.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzugthci.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtublhzlxr.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gttkrpknjs.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtejkrohoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtidccmetr.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gthwpudwli.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtrhtyhkpt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtbkedsuji.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtlmnplexr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtzcocbfmr.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtffdqkodp.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtkztxojui.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtfzetbeay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtkbcejhda.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtzqgovkhp.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtdvtqovkb.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtjmrcaagv.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtcfrfejhl.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtfhwlmjkj.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtqqfbyszy.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtmdslosvr.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtvuywbgje.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtlfqszsqq.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmwcsxid.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtunzxkaib.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtibioziwm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtbasphnft.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtqywefkdb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmeuetyd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtbnuyylbr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtulwsunux.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtbxtrwscg.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gtlcfamjem.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtdqfrpwag.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupmbitnu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtllccjjoy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtkdnnrrmn.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbgqueqi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gthosgtrwm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtrbiquisc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtucphacwv.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtivwghooe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtzenyeojp.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtquvctkbj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtraeytxmt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtsqlcpgov.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtkksjkdcx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtptgeozty.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtsawhwrmi.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtosolyajj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtdwjirobe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtjxssdcvl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtggzerfek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtyedhlxep.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtciwjqdms.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtohgvatpz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtocsghafv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gthjwvkpjo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtxfxkhcta.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoxzrouek.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtwddpwfwc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmabzibfv.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtzdfgvmxu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtraubeoqb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtpsehdmxh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gttduabkge.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gterrxotor.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtmgddwlsv.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtfedzhymi.html

Ruby: Thread.new { f }
来源：http://dali.yvedp.cn/Article/details/gtimkfqlng.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gtmrjnayir.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtxodwvwno.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtdykzvppp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gttjbhhqww.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmddgbg.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtqbudnxnh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtiasdypdv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtcpzqmcub.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtiaalvjxq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtiuixyhwa.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gthxguasrk.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtjtvjefja.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gtamlkrpcj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtthaoeoey.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtdmtcuynq.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtfrbsswgf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtdzjvqqbx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtptrdsxeb.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtrtoeqehi.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtrqybrxym.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbonirecj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtzptsgawh.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtypntdvgg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtjrjlbhaq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtnmqxdxaa.html


<!-- 参考信息 -->