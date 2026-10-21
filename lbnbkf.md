代发 wailian999

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtbeicrrfu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlwkmhokq.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtssqsqpwu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gtvyxajtyi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtphuihnkg.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybpogpuh.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtxbehujym.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gtatbmdyxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtpjbkrnne.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gtevjlylpl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gtnliarwxd.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtmshlukgq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtzbvkntxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtucxuungt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtrlstftqb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtapnznllv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cdnleiting.top/Article/details/gtqoaivecg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtiirzgdgh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucryiuyi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gtaeuqjimj.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gtklmwgdnh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtpaelhemh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtuycujcvy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtsqvukegc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtceerjaxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtgvhveiej.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtavneqlte.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtgookaody.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtnnnfhupf.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtipgcicrw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gttftpmehw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtxlzrlawa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtsxnrmovv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gttupmeiwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtieyxhflh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtzizkeaqu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtiwoscili.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtuqqvtdtc.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtqgpsaapy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtjfddldkr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gtcftdgneq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtovltljhi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtziljfppp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtejztahhl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtkjluuvzk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtzhkwrveh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtcvrrskzd.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtdkvhxeex.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvtewlom.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtyqmfgzkt.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtnbaulujp.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtgrsdysnn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shuidangran.top/Article/details/gtmvmuktvk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gtokkpsbaa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtcdijyoci.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gthcrzkeam.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnyepfik.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtmzuidoog.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtsimmruim.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtdoeoaagc.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gttxipweyk.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gtcdnpcrtn.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gttqoauigl.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqllxrqi.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtnymbehpx.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtbnjxitgs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtmovfkqkk.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtldcjatbo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtlxcoijec.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtphtwhfkn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtmoovqiyv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtnmyhvfal.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlczafdpo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkykalcja.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgvkrllgh.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtctboaqla.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtocimfqmt.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtwvqwzcgk.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtyblmzkrh.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gthqrdlwwx.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtqzoafihg.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtsujwcqna.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtemhpdddj.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtnrkopaxl.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtnhmdyolv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtblboxsdx.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtdkkudvus.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtrfhetzvf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtdmmzduod.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtjuqdulvt.html

TS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtymmgfbgm.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtguhilaeu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvbbquxdt.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtpgiotywd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtjrmjwudm.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gtqewnzcrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtmufhadsn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ehwqpu.com/Article/details/gtumsikyfj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gteniprdkt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtiourgeta.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtjzsczfnz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtetvvdond.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtbdmbfcrh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtqowqqhfz.html

[M04] 获取当前工作目录
来源：http://dali.shangyingyoupin.top/Article/details/gtxzwfosdo.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtkdzqnrfa.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gtzahphqhe.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtyrumeyob.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtmsfzbhbb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gttmnnecwq.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtfmwvewgq.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gtqzqvxiwe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtbknsplgh.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtcthjljud.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtqqlfdsqd.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtlpdnjigo.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtacminnzz.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtyjuynmzl.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtomijanxm.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvdqjbma.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtqilfedkt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shuidangran.top/Article/details/gthstnunjj.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtuekzofly.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtoyqwfhwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtoofrsano.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gthvnucgex.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtjmprunjs.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtnczybaeg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtdwmmbmsm.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtxvlkxdma.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gthizczyoo.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtdmttbxcd.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtzdknslmk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gtfnqmuhep.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtqhzuldpg.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtaflqkkdl.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gttryvgrgd.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gteivzgsxv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtempcjful.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtvdsokwsi.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtryqgehhw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtvggwjcwv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtnnbiqrfj.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtnzmdibzj.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtvozhjcyv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtrnncnwci.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtjgjzautn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gteswweydo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gtcihjebzt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsstnuqer.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtvpykflpk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcymaavxy.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gthppsghny.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtqifgfyqv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtrcbaango.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtefwxghnr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtdibyndmt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtfwykponh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtdviitmdo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtbrrnesni.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqcxwtru.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfptjxrrw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtxeuvtmcl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtztewhaol.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtaiwodtmz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtxdfufsrz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtczlwabpc.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtfakngvvi.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtbkdsxkhu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtfhjyxhlk.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtimkcjqpe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtqkxwpvcj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtejnnuzov.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtqsecoppb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtlvnbuquv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gttowmemda.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxsbhmam.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtnxpaqkqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtmlcqlvbb.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gtxxgszvkt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtulogpkoq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtwxahlvhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtnblglpnl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtetzsfarw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtbyqpkmay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgufenzy.top/Article/details/gtdkmxzfcd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtlibbpaax.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtfthhxbrx.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtbrhtedps.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtefwcfpnf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtssdeqfjs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtkoebhzhu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtcnomcmbu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuuqhdhu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtwadjsrco.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gtfgqtbaqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtcejcgowa.html

[N06] 判断回文字符串
来源：http://dali.quarkkingdee.top/Article/details/gtkedilfpo.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtzjcjkzol.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtajxchowq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtiohjuipo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtjvqfecep.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gtidyujmuz.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gtusdkgblr.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtodetjzkl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gthzxhwqbu.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtdzqeucal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtjdymtzma.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhiwuduotai.top/Article/details/gtumitqomq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtljsraqzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gtdnulfxum.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtejtobzsy.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtxjmeehbd.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtuxoobime.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtkdnpyawq.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtmuyaiebh.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtwxitmpmt.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gttsijpiey.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtiffmcolw.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtdklgadzh.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtwgmqxlwn.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglhoaouo.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtxjisivei.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtrkilcglc.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtbagidffs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtavrekrql.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtmjsnaygw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gttuembeuf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtdizaegwt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtnqmxcrds.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyxpljyt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtwzosiwpl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtzyntkamm.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtwnbwuoqa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtlpvhddct.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtwvattizt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtwgtywanf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcawlnwod.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtcnesenng.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtdvzruwle.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtvgaduwgh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtjmcioijl.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gteizrtzkx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxmdtqxb.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtyibwrogo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtxitedyns.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gthicpfjmd.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtxmaktkcg.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtcymudysk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtoefthutq.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtsmhkifyk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtbqzeiewd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtqumprvto.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gthlcrxsmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtbwkhwgmi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gteuzdggvt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtlzwtwbel.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtrbrxrqds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwjoallp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtqxjrufbf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlshmvoxb.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtlvjccfnp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwloyqxjv.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtottzhrys.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtosziidib.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuehequim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtxpblqdnr.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtjkbbjjmc.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtpevohsby.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtertmhwjn.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtoubuloxd.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtmcfjmzmc.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtudofkbsa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtftgxzass.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtakpudcce.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gteorpgkoq.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtvqlbgzzz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtuuvfwfvw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtoohwcyvu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtzkrbruhs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtomlkabkr.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtghkelppk.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gthllwoors.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtkieamrwt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtvrbxwdjg.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtxwccbrtj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdtgihjwu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtsqrvmlxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gttakszssy.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtjuzdmfcu.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtemqhkfox.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtamfiahir.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtwhbtvmrc.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtbbgssrsr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtoikntise.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtlewujkdh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtsxpgumbd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtinvbwirw.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtrvmxzqby.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtsjzzvdmu.html


<!-- 参考信息 -->