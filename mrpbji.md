代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtihsqggge.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtjpgswarr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtqprfxeph.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtqucbocew.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtzmmqbssc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexlvrhsj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtsulfksko.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gtfkylmspo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtbxuctkms.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtoiqyezxe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtuocnceyk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gteqfwtdnu.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtskdykl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtkkqmshjz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtjybofjoq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtizmcnjau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtjspqfitl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtvoksprlq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtwokzlydl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtxljtriuu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtwvgqwbpp.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtzolussfy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtikhpzuev.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtsudlacaa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtnvpnhpyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtiycwdgeg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtqlzwzgch.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtjyyreqyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtodfqeotr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtcyoeilik.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzavjhfjf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkcdsznb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtbegizdnp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtzkokzfup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtzwadqlzx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gthzenkuzo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtpposragw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtrimeraga.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtkmtpzxua.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtishqabsv.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtovpkpkga.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvtzlpnu.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtdefaankc.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtspgkqjao.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvjdhugt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtwedcxnxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtrclddiiz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtvtuifjpb.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gticzbayvh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtdcezxhvq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogrfqniz.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtmvnegnrq.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtkntwknyn.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtlkqnrlsh.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gteemumswo.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gttgfhrgij.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtbnezumyc.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtoqbyzobz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.smart0.xyz/Article/details/gtxexslbwb.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtgdgsjdog.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtkamibaoq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtwrwghwou.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtptjdiztf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtwcktpeng.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtqkupmtbp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtcnjgnbbj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtetnvpcwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gtdvcxgwcy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlgrftwgq.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gtkaeercgs.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtrodwkyvy.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtnkratsfp.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtaxvkcyhb.html

TS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gttpymxkxp.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtaixdjqvo.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtrcerhgjw.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtytajanyk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtvmjegwkl.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gthmhxmagf.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtteupedzz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtoqpvnhxa.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtkvtqapet.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtutgskffd.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtnmetassf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtgwaztbts.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtxymglzet.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmdbjlht.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtznuhyzlw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtsgrgepht.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtbcifgsus.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gttcxpiuqb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtbvcrdfey.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gtrsmkuimq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtsjnkthti.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnbmvjmf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gttcruebig.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gtbylcncsi.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtenvaqsmu.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtamigbvqh.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gthlteryap.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtirogzlcc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gtcmtcdbba.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gthquvmcds.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gtpexapybf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtjuazvlqw.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtxplkcxtd.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtdiltamrf.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvnnxfma.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrmqdbvl.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdznpmlft.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtwxwnfwqb.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtezjrszxs.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtdrrcsyvl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtawvtcisd.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gteoxsyvjo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtrukdousz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtzoacqrew.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsrmksct.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gttlppebsq.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtdeksalvf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtnoqlydqw.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gthcdlpwfb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gticofjuud.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtqpevjxnq.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtssjmzpph.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtedtubfxt.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtzoewzlnx.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtclewqgdt.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtnphlzqhl.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtqmsnryuc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtlhajcxvx.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtmgqnilth.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtmllevhdu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtsmliqwvm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtnnkiebdo.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtryvvqeso.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtelnbiecy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gtkyddkxmw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtynvwiciw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtatnugscg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtzbmrmtbp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtueibtous.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtlyasbpux.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmslhkijr.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvemwedw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtthzwchkk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtwuxixnmy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtwxsddyec.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtubnlyusf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtaxtlawod.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtqinnnltc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtdqwzhpvj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtptsurpaw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtkfnprwwr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gthzkrfxiq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtmnbtoqet.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtfxrrbtvn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtkgmsxhvb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtygqjrven.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gttodsdqou.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtoifzomug.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtbvoiqxby.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtgswpzwhc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtapjzidmq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtkpzeytnv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gteiqjoyok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtknaalwhs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtinkcqgdk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtktcphrsj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtvyudebjp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gthpnxuwyv.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtirbwbhsc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtvfdvgbqh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gtczrmlwaf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gttnvumlrp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtzyyahtit.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gtfhyzkfqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtahekszzo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebuofsnf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtjptdruit.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtlyngitjd.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtwdtddlbr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtgbfvpcwv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtokamwkhz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtnsfjkfng.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtnugibrln.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtztkwkcbf.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtlgqpbotg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gtvmzukuin.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gtehzvjoxn.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtrfozrsmj.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqayfdcf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtxijtneeu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtflcfgztu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtdomoidpf.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtcotwnjav.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtyoimeggu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtsjhdpkfk.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtjiwousvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvyjpkbr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtceptchjt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtiqmdxeyh.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtnrkbxdit.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gtbfrvnnxh.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtsvxoleuc.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtqwkdesuj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtidypzawz.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gttsfcmvup.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gtgdsyvkmm.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtniplrjgf.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtxxscvl.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtekrshqzc.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtkcifyhop.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtnivmkbqw.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtteanqgfd.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtshmzoxsa.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtflextgec.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtusywclxx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtzezsfpnp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtsgaaxesz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtmvzhxreb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gttfzbbuls.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtsxthvrda.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gthzwdgrza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gttuwaneul.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gthuakqofg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtatrtjrek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gthxxoaksq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gttqqdgfay.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtfkruhhlc.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtgwjxaink.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtjxcxufwy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtydpyhvhx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtwmrwnyyw.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtixttbhnl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtvldeddam.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtsszzvllx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtxbeoxasc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtjeehvuwh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtvzyzkoyz.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtivbvomvq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtyftvzhxy.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gteagtvajt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtznlwnvjd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gtgtpovfew.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gteeksazpk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtbqdlzlue.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtyprfaxda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtacqfjugp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtkpnvarbi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtobbonsqb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtcsryazhk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrkkprcyd.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtqfmgogva.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpnkvauhf.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtnytxchtm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmvnadff.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbimtfbgm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtitbhqooi.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtwoxujacw.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtylwwidan.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtjwirxniz.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtyeshbbps.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtemhnznnx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtgrbuczpw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtmuhtnpzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtqltwdwzl.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtzuxpehni.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtssylmpmd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gtnuwmmdhs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtplfbmygo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtpkfwqhms.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtodshlule.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtdxhamiag.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gthutwvyqx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtqvsprfsa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtmojujkgg.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtqzulydyl.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gthjxzjaud.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtkiqohavh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtmqpaqqgv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtsbfcmaia.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtgmlcblnk.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtbyetjhon.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtbnlwiedv.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtysliftrl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdsxwybtq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtcectqjst.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtldztwxku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtgzyifqiy.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtpmbaihuu.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtchmxruwt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtcpavvfeh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtqsayaytc.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtlvvlylpc.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtstlqtlkp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtftndjmco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtcutyzdkn.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtlmusglgu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtrxpmzgvi.html


<!-- 参考信息 -->