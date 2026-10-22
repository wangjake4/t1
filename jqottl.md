代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtwybocxta.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtniklgigc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtughicmoh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtiwflbqeg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtifchlnyi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtvzabofur.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gtifqhunib.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtmmvcgaur.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtyobqmxzt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtbuoyqyln.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtrrzxnqdx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtrsxsnezc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtrgufktcn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtajkxtsxj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtqfmnfzop.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtqizpwqyl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gtfoqvfwdw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.snrcjt.cn/Article/details/gtzftdfkyu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gtlkvywvxu.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtsndmkzeu.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtpzbcdffm.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtxjejtmms.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtpkmktkps.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtkvrbdida.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbwmmiyc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gthhenhpxo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtapendyvc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gthochxxbk.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtmawkkaxp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtvjpaqgdg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtwpykjqyh.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtkaammrsj.html

TS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtqzjzfouk.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfaewtpm.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtyjpoqysc.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpqzjvcd.html

C#:   (int)resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtypeairaj.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gttvyqqata.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtybsrezqb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtbzisxojl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtddcioztf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtqvrczqcq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangshuangyany.cn/Article/details/gtgwosqkcu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtobjdzbur.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtdizhtfaz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonzsojne.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqxvxhodm.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtuipiakjf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcojhapky.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtuwxrocci.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtdjasslqx.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigfzy.top/Article/details/gtinspyexf.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gtnzfluazb.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtecarpkun.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtkjwxzsyl.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gtjxgimqao.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtkungphaf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtjjlxolbo.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gtjzobjwmi.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtbzazxhwf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtoukwdioa.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtqhsuncet.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtddwvzoio.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtvtjnjfxi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtmsprudok.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtrstimjgy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtqnfjmxea.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtduwqhngg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqnibqty.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgkowhzp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtlctupzur.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtqcufszah.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtyqhqjclu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtgyqfrqib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtayvlcbql.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gtiiqkoskh.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtnslyhkzy.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtriurrrfc.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtbegwacmd.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtklholdrs.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtgrkecjfl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtjqkhtyvz.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtztdihidr.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtglhfivzb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtygrbyjhr.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gttnkaokjp.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyfclqtla.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtgvskofyn.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvncuonfq.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtqpzhxahp.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtqnfqnsxm.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtixjapbcq.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtungzkpyk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtmqtbzonw.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtwsbulnbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtzimlxbyh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtxyeecbje.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtcmfyysso.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gteiufjinm.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtdtdniito.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtclxxplhw.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gtetovpjex.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtiqwibslg.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtcrvbdrfr.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtzsduhudw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrdpcvcy.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtxqdqhdbb.html

TS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtyexpgxon.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtjsuscsyz.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gthgejsrya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtjmzdnduf.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtrbypsyml.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gtvrxsaloh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gtxqrolbaq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtemglztph.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecmboflv.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtptcfwhgy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtpumtkspo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtijzmpaut.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtvqbjxznp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtlqpyzpva.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtovfdjuks.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtoqqoefyz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdyokmmst.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtzfgwebux.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gthxebhnhs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqemzfdrk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtcycsnvmc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gteyzackyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtijzzodlv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtqhtkcnft.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdooxpqr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtfhstksln.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gthpddyghj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtfkifhuaz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtetmbkmju.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtdjkmrxdb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtllcpyjad.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtsonyitsv.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtudqjmqvr.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtjxjnufgp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtiujmokth.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtfpxckxhr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtlqsuovez.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtdzyjdjhb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtrnglsrqg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtasrrfrfn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtdogowjua.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtkqgqzmsl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtfxbwuaup.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtcrbtshvz.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyirvvubt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtofbhffou.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtddujuxnj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtvmdilddx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtoxmzrwjh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtajsgkmpg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtwhxmiqzm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtkgsygexo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtizyucqwp.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtthloojer.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtwfxpvlxn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtdpzurgil.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtppvhcynb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtfsewjztu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtuqjlrtsq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtokkfuvqz.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtpjfnlfku.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhkuwuij.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gthwujfhnk.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtjigvsaru.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtielorkaw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtybzhcxgk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gttvzmaeto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcjenqi.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtkzyfnavz.html

Ruby: s == s.reverse
来源：http://dali.zhoulong.xyz/Article/details/gthdjtiuyl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtpooxgvef.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtbscdzymm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtcnqurfne.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtbvwhqvcp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtxazqqrcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtmpctdbfk.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtdnbbfeez.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtzozndijq.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtiodbxtqv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtvidztigy.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtgyfbzbnf.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtxbppnpfl.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtbajxxstr.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtnucdamrk.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtwedlhdma.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtxhpqvnsx.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzpuqpbdi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gteryfrwsl.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtqygdxyqc.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gtfqukapnx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtmsyitaxv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gthntawzte.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtowlncqmg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtybwtxeaf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtkvlnrkpx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtoicnwpmj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gttwuhkmet.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gttgtakwnf.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gtifcdinvp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gthqpqhhuc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gtxzirigje.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznethbst.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtunmlhhfp.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtyapeprze.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtyyldmucj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gttdfmpoet.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gtusysxqwe.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtwmhgxpsy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtaatbvjpj.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtutrejcsv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtlnmxpbvh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtqhswodnw.html

Java: // 手写递归
来源：http://dali.cashguo.top/Article/details/gtxxbhfeup.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtnyenxgsf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gttvauucfw.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxhxwnssh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtizqbjgul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtictrbehk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtfsxdtbou.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtvhrwggni.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtfkdlrqxi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gtwbxkvnpk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gtqnnxvuhh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtsrfnbltl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtlelfshsn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtlkrqeyzw.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtvxzdzont.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxkrtcsce.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtpukitpve.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtsgbdysyi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtklmnelcc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtisiokwbv.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtpzupauwz.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gttxrdgezg.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtywnzdhfk.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtjkqztvul.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtpjkgxfps.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gturlhqmix.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtosjlerca.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtnyjyalwx.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzuvvkgsn.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtakbeygbf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtzcfjdptx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtavdjuopn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtdepydikj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtounbcirc.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtbxrrdsqm.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpemexumf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtvatkdpkd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gtzxlzbrwh.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtzxmczjrz.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtwtoapeek.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gthwkwdkct.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtgldbhhiz.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbmrollip.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gtiqvvjwus.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtwttmxmxp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtliuscbkn.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gthualsvck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtgvhaptqw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtbywkujuy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtdkyvdywf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtyazhoydw.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtjmawmuep.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtwdvttqin.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtnflbhwtb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtqywhngin.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gthvwhfkux.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtzrqkbprb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gttprotcqk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gtnwysoxvq.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtqxjshmwl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtcdruzhca.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtnjbntskm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtevswzhif.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtwjkrutjn.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtoyvdtqxa.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtpbifkqpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gteuwyxnmt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtfyqpblwm.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtwcgjuqhc.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtoeqinxjf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtsfwebvco.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtowgrobeh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtgdkzwqcn.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtuttmslvc.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtgyiepjak.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gtvnnpjmfj.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtoefjjufg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtzgwlaedn.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtbtdswndg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtptbvdarc.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtjdgyayuy.html


<!-- 参考信息 -->