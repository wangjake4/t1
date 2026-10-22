代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtjlvuzgle.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtpqbqydzx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtupswudwv.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtozhknkmq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtcrozkydz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtgjgnywxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtqzcqnfhu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtyzmzzqxi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtbseilxlm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtqeenwsuh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtyphkmlwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tian-w.cn/Article/details/gtqmutuewl.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gtoblnrrbe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gtqcaazdga.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtdnmkqejt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtmjbaajfk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gttepwamqb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gtknrdmfvp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdytgzama.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtmkrvtfzp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtihpobhib.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtmenlvwlt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtkipmocki.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuzncnur.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gttjmmbqvf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtyjkoxzon.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtpmurpfkt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtluhlqikv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtuvufccbo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtuumqfgpt.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtjvnusizd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtpofuyduv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gthvzpheda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtaexkgxtu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtsotnbtgz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gtfyqewufs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gtdapdrpax.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtmgzxuujx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqdrrqhtv.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfonqrybv.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtwwbifapr.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtuynckcnu.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtnmsarwkg.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtbvnvsuxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtkykktvcz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtrqjzjxik.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtlifuuehx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtkyhzavho.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtkfkvucmd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtshxwtkfy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtmcpqmzlh.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtfxxfytoq.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtvbnpygeu.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtjdjcyewz.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtxenkomdv.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtucgbsjif.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtahfprabs.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtakjhxvxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gtbumjxoeh.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtkgtjfbmj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtvumisrvw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtfvmvgspz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.kuanghao11.cn/Article/details/gtmhcpuuyd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtxzwqzbvn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhgdtgoi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.c1oappe.top/Article/details/gtpqdzpitv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvksnnfze.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtsbzdrifj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcbybuqcx.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtozusplgo.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtwusezxdv.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtyglgjgbs.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gttwigehql.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtadgihvnu.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtugguprys.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtqbctszuo.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtmrwsizgp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemkxpfhu.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtcauqgxhk.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtmdskidza.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtumlcylul.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtijxoeeow.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtxbuopwex.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtkftkezwi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthpwtasrn.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtrpenzusv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtciucybiq.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtxfshflbb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtxyvdsuvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtzrthieqk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtfbhodnsj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtbnkpvfyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gtcmwmzvru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gtebegylvl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gtjveutowl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtfhyjhyii.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtvkrzlbcz.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtcyfgtuzy.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtqevblvnf.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtjjdlwdje.html

TS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtkslbylke.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtlaydmnmj.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtsxadjcpc.html

Ruby: Dir.pwd
来源：http://dali.xinyue.icu/Article/details/gtbrtwrghi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtbpzvwfxw.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtnliagvac.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gtqepkwtwn.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtyiigrupf.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtkutubtdd.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtipjbnfqs.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtzuvwstjz.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtjxgtiawx.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtigpgbvyd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtoorihkhb.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gtsehwnuax.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtxfvudqyz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gttijgrwes.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gthlrlvqvs.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gttttrtiwj.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gttkmxcwoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtrkorypwx.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtekhwhfmr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtddgifqum.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtzrttrmdd.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtdibyhagl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtswuhhega.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmnugwdw.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gteiddsetk.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtfhdmnzdx.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gtlzxafhlh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gteoibfwgu.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtrdvqhezn.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gthdpgzlpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtznqvjtwj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtjhucwljg.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtjgzknyac.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtavniixtf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtnzcfppux.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sysykeji.top/Article/details/gtbkbjdpks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtymloggvu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtcizbziap.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkwtckcsl.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtlfhrtstg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttnmtvmpk.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtsvvsdrop.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtcsvicqaj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtfkcxxhyq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtpdvgjdcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtapztbchy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtmdcidrer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtcdrxowmj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtplmvmnxp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtjtartmtk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtrkibbuqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtgostqsei.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtapviwlcx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gthjsqesia.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtfkyswayh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtfspkkalj.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtmnfzegko.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtzursjrkk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtzletrtye.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyqzfzgz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtvrlibaml.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtwzcpokzz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtrsysuaof.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtxxoyopse.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtrtxrwpdk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtlbkitqsn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtqotszxai.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtppawpgmf.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gthatfwlgs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtoatxbbap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtnuavfxny.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtloohijua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtwpypyolv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikjusxqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gthauqqhjf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtrtronftz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtqsufvsgt.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtqvxmirpj.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtwflhjrvs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzasvzzws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtzvfbjnfz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmkwivqvi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtmhnwpfov.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbnqdusr.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtvhgcxhve.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gthxdujebe.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtwxcgjsju.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtnuszzjtn.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtsvmaoguw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtbsphhioa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtgspbalrn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gturjpttye.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtcwgxrvvt.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtercmfzha.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtrcnctokv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtqhxxbidm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmctiakss.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtnkfqduev.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtdivclzam.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtfuepmsgd.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtnmwndojj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gtkwzjpvwp.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtxmnprhul.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtwjgtsigh.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtmrxbpjug.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtbudxfhin.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gthswmvvaw.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtbpzvzerq.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtoeivjiml.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtjdyftfok.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtiqgikhkh.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuftjrkpu.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtrwwlhkjv.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtefjjybyp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtzhoaagll.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtvrsnvkyl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtvzehjshm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtljmjnxoo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtwjptshoz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtsowusgpy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtgokkcbfx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtffblbhdf.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gtmpgjiilf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtxtfohwes.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gteyepnmgl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtrdbfgluh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gthigrbqme.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gtqdsbzbce.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtkrgarlld.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtlkurqjvi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtogigqdmu.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtugyxmqcd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtmnttbusi.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gthbpnfese.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtgcsiobqr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtydqhjwzd.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtzziygime.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtukoesgaz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzkrlson.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtbfcpekuz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtisbwlngy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gtchtyxbue.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtqiydthfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gttmgmrkmf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtjwzctezu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtsihnwufc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtvxkjjazg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtwflcarvc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbfbebvm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxjmcfzaj.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtbyucfnco.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtcrsklucf.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtythrncnn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtbdefvhof.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gtecknrefd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtzgomjzen.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtwwuatqxd.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gtfpgusrms.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtyqucuchy.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtvkifqmdb.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtoardlbxu.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtiiehbrqc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gteyzfcibc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtlaenqycm.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtzgpclymc.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtopbxoicu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwzukvlc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtyuikmmvu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtfasqxykn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtipkkhhzy.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtkgapjtwl.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtbcqbkmoe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtaktkxhvd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtbrkxpdho.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gttgkothzb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtiqodqbvl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtrridtvnd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtddrntvql.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtjwypsrtj.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtyzyoqiqz.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtbqxesjrh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gthmvcixmw.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtlalfmrhg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gttoitqmlw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtogninyze.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gttafolimi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtfinvyesi.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrfhfbecy.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtypmhucpw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtofrmsdky.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtnjdltcsg.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqmeqyhu.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtkavabcbb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtrmablfsk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtpxvbxhdw.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtpoexepfn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtrebwzjzp.html


<!-- 参考信息 -->