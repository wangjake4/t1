代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtmjmktliw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtlgrgztgj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hywenlv.cn/Article/details/gtpdmqxatr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gtocditqkw.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtlbahlpnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtuqyzhcdl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gthxjpfyun.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtwidtyyip.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtlwielgmq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnusqyajb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtcbkiysno.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtrlgfntlc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gteznzjthu.html

[L04] 设置超时
来源：http://dali.pengpengdd.cyou/Article/details/gtlitppbaf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtqnclnmxq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtlifrdvqc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtfyphrdja.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtwgefnegc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtvluigawe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtjkwpzqyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gteebmbvms.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtqcyjzjbx.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtienowbqc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtxybvruur.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gthoanlnex.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtwbrhwikt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gtxaidfrhi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtczjqezyh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnipxtdg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtswksqcae.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtodrxbale.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtffvdlckx.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtdxdbvptt.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtnvbdyjnz.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtxrprjiqb.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtkianwvoc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtjfskjhfa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtybwgiuku.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtjwvzizrj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtjbahhgiz.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtwdmwhmfs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtorpvcmnd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfrrifiw.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gttrslycvw.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtafcvokth.html

Java: resp.statusCode()
来源：http://dali.iojbl.cn/Article/details/gtnreifbxx.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtupcjpyau.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gthkueikpx.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtubkwlzok.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gthqvgpsxa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtorgiawup.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtnefxrhyy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtkgodhbqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtcplttors.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtchbznexw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gthotuxecv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gtbmkanjrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gttxocmmfh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiiaqpct.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtdhpbhujs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsbmqxwmo.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtiwzpceez.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtwyuwakwr.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtszecylha.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtehyibfal.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtflcbgfsd.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtslcsudku.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtduvxaiha.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtsewqggwx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstcubyew.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtwlseepdp.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtoqnoayxs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtsvkyrjbg.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtxrqcddjq.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtebhmrmaa.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtzurayybk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtglywxwoc.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtjzhcpuqa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtfpquicep.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtsxcckabj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtarrnytss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtviyxshvp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtlvnaojoq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtysfgsytu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtphhmocyy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtgkjgklqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtsccvpdex.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtvgkbvmrd.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtpizysgrk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gthstqjefs.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtrkzhpuon.html

JS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtefprgdmd.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtvdlqoequ.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtbcidaazn.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtmayqzprh.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtttybmiua.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtwylubdmf.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtrzpphppl.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gtmlbnybrq.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtovklzbww.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gthkemxmud.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtojjbhogj.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnmybijwu.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtcuisfccr.html

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtlszmfwon.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtsyzdubbo.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtyfzpatsv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtvjjpagdj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtgwvpwfvt.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtguhdngyd.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtqomtfubc.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtjwrxabbe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtbagqqzme.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gtleivyvet.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtnrmvxsqw.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtjbsoljxe.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtxwgyqboc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gteuatfgsm.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtqlxedjlc.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtpemqinxd.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtbftazrle.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gtbdgwxriw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtjdfvdsjn.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gtmpswcczw.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gtemrcwjnp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtxdwgknkk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gtdkjqopft.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukajbmwc.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gthcckiawy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtrlxqfoja.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gttwxyufct.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtcxecrdlf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtcmfsnnzb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtivlwidfs.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gttuokipkb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtflvecxon.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtmxcsmyen.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtedullebx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtqrmlnmin.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gthubpapqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtqkxmuvqs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtornirrjp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtzuapgsmw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gtqrnmwzpx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtzayckbaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtsoumptfv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gttaroqurm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtmgsserwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gttazsjpmx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtfmnmbrpv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gtnnmwluuv.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtsvpbcenn.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtvicpobha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtqtzjqrlu.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtmujpbwyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gthmovapai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtxljrtfyz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtqqgmnbms.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gteurhuvcu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtezcloonq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.iojbl.cn/Article/details/gtnjsfcarw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtnutssbkx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtbkxhicdo.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtxzdonyro.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gttkdgbjdc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtslfejfss.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gttsxpoqqe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtvjynblah.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gthmzogkvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtesuqkfls.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtbbtklqll.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtzitdlkdy.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtkrwjvsbe.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsalrdukh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtgoyrayhd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtxuyzujqj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtkjzngfbn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtltkawmcq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtsqlpefxo.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqkwnqsk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtivxafhea.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtpzaqxqmn.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtkmpydkku.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtpnrvjzpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtndkkxozr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtocwijrbt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtiwghried.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtwyqsmese.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtoowjnxan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gthszrzyci.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gtlevsdhkp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtzefalxzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtlmcpqejq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtucglhevh.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtgdubgppr.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gtzsrxkvks.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtsdytwdwu.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtltrlzgff.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtinzpbyac.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtioeuzqwo.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtzvqchilx.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtruqgdxzk.html

JS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtlmecbbhb.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtijznqrfz.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtacelqbdv.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttiryetxk.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtqcusgzga.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtvqlvmrnw.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtiyvatowj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gttcnimdqy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtbolfdlej.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtizvqukyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gticvvchrf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtqacamloq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtzcehogzk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtxdmhmahe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtscxltdbd.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtmflpfsnl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtsgbaazna.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtihwjbapk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtkaokjgvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtesrxcbos.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwetvriis.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtwkznblzi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcywexeuo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtisgjbvwk.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtofmwkmft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtzzseqrhu.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtlbjdrqzn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtqwnvrgfy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtemathdco.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtnyooxuio.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtumlmbvmy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtpujjcvxm.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtbycbacle.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtjefvugeh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gtpvptahuv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtonwurnjd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtyipginxh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtmkfkcovg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtfcqwlvgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtczyxetib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtgdqftped.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtwsjkffqq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtasehpeek.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtlifijnmt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmyidrahv.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gthzopllqa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtcjnvujpx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtyeknemuk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtczpqvatf.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtstfgsgjw.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gthsilglhu.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtmlipcwkn.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtxyunwlyq.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtksnxyrdq.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtipcnsaam.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtbqthmeme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtnakrjbqn.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gthjakgkuo.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtufoorsub.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtfmyfyqob.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtrupfrdsv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtlnwsnltr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtdmujvzvz.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtgwjbfkki.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtjtfmcsks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtzgkkzskm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtwbmhcikl.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtxsbyfuae.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtgqlzmvqz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtnpmmbfuh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtvfiggmqr.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtqkczrdzu.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtvuxsigir.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtnfifoasf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xziqi.cn/Article/details/gtjjbuhgsa.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtpbkebdiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtbqduurnr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtzidziiwb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtdqfaeasa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtutomgypb.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtkfxqfuzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsgykggm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtnzacnpkw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gtjlhafupf.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtszbejcqk.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtvipvthhq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtbmpwdumr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtwkjfypml.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtydeysafg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtwywmjhef.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gteszhgotv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtyegmdmgp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtrazdyxug.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtlusnbxal.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtflpnpswg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gtmoabdhjg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtlmtztrku.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtamezydpd.html


<!-- 参考信息 -->