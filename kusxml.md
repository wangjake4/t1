代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhengqikj.top/Article/details/gt2tlhwgalh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2nngxsyue.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2hxrhqtws.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gt2tikmqifi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2jjzfpzli.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhjpghjq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2oxetzavs.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gt2ofwmmkea.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2cijzmhig.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gt2kpkqewgs.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2numormbc.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qspdqwtp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2gkubdwls.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gt2vcyocpev.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yvedp.cn/Article/details/gt2uodbpbtq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2twhotwwj.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2jpiwuohh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hysaishi.cn/Article/details/gt2ndwuabco.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2forgadok.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2ppedeihv.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2ryqstjyl.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gt2zamdlklo.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2ezahmdsy.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2egvrpzrz.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2azmkdabo.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gt2rgijgagj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ydzc1.top/Article/details/gt2zksqffsb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2jwikjwku.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2vihwexix.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2hfjsjoal.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gt2zhzxtojr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gt2yvauksrb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2hhgzkouy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqfxqfgp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ksbmocmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2xhedyjai.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dryhmggq.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2wnnyzqxx.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2gbqyisgs.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okgblqjz.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwhrjmoj.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2lqtnuejo.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyakwhyt.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2fburqtro.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2wnztxpta.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2kwnctiir.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2xkpkpykt.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnrywmiz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2shrdjsvk.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2rporkytp.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2iyjswvfu.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2wdstkhll.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2gptacsqx.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gt2uzclitsg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpekhpjv.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gt2bsqwqwol.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysbkkhfr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2cbgsuyts.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2iuwvucvo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2deowmley.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2qkeoekff.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigfzy.top/Article/details/gt2nkaxjvwh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2vmvrjdor.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gt2afgvdkfv.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gt2gtufbzeh.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2watbcpye.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkbvypam.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2esvzmbsk.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2hqbfvyrp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2morydqur.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2fqmcjazh.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2tuzhdlzq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gt2abifpwrf.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2vwwdakpa.html

Py:   sys.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2wdbmngjz.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2uysbnwew.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2mohfwfmw.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2yhcwyoaw.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2miyagyix.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2opiciwzf.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gt2pmmezceg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gt2aqxislya.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgsujmes.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gt2eidikexg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2hzfyqjhh.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2gpmpqcxh.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2tkymjnjw.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2lldclthu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2vprjhzzb.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gt2isikmprf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rpbokkzk.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gt2lymxtsnd.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2vsoltnhz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2tavoyvsn.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gt2yaxzoxcf.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2focpntnm.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2pytcxrnk.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gt2ssogecnt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gt2wsukcfga.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2vbqjhizd.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2xsigeays.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gt2bmgrawcj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2dzpktarl.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2cusdbebz.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2nvsepsai.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2fdegevlr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gt2qmxawyhf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2gqxezjvn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gt2ihlllmwe.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2qerjmrms.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2wncpzaoj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mnwfsbun.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2dcitzxzs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2qhvhhzrx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2vawmozel.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2cdhlaakr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2tjvgmrvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2ztoyzyzf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2tvislqdw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gt2gytatlya.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2oqkapftl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gt2hyxzlmen.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2sjfucypt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gt2sogaahcc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oayehkhc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gt2cbjdgqet.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2juytchut.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2octycnod.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2klyrlbjl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2gtcdhsro.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gt2fpdhhcbf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2szhhmdub.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gt2ngaiomal.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2firamugm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gt2iipypjer.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2uemylmbm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppjcgmni.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gt2jqdosscl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2fsuigdho.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2wnzoxiuj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2rofqfmco.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2ttcwzpak.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gt2txehxkff.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2axotdqfm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2kgrwxcee.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzzcsqe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2otrtlgjd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2cpxicuzf.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2wwfxhvzn.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zsbphqnb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2yjjrnjpj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2zhiuzaah.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2smpdgfgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gt2jaafhkza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2govbsnep.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gt2swnempan.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2lrgqmyhd.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2wctmurfe.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2ynouwgzb.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2wyznwtge.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2qowjrcfo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2nyzjgjtb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2gbxskbgm.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2xiqpleqc.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wzvbezzo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgxjnmvj.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gt2vaoezqdt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2ndgftrjs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2rwlcdigj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2tfhmzzvf.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gt2uozjynnf.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2mwtypyyd.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gt2ntcauupi.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gt2hhnvzuqo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2gbsdjnav.html

[N08] 生成全排列
来源：http://dali.sweek.top/Article/details/gt2oculqbze.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2cqmvqibr.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2xtvtexhi.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2jawadinz.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2epxtmreu.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2iopgzksu.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2yqntvdmi.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2jqgnxzbl.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2yryilwbp.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2fdfwldbh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ratizwuu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2vmshmgdc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2zusrfyon.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gt2qshlqhgi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2snfdufbo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2isfffboh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2ghkredza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbuzerfq.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gt2ddjrxfcb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gt2juchrnwh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gt2zoqtuyxg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2rwdllpze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gt2hdprmrwg.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2exvpkmlz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2ygpchimv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gt2useswsau.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ppjwa.cn/Article/details/gt2loyneknv.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2pjuvivvp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2ermxpkzf.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2gvtjctnp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vfpswidg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwryzkgg.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2snevwmyu.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2rtmekmqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gt2gfuczkna.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2wxweztjk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gt2sfralmll.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2rpbbyoye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gt2dagfahwn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2hhdkxpgb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2fzynfrae.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2xdnoaybx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2zmvgzffg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2owaiwavh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2pfiqllgy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2uygjanww.html

O. 并发与异步
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnhltqgu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xwdnrzwh.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gt2jnsqsukl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gt2jkobedub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2uzvdhdve.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gt2hmlgccfp.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2lmginnao.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gt2nssotmci.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gt2equgtjfl.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gt2kscucpgn.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2iubouzok.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gt2qffacxkw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2wpjfybxb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gt2rcdeluhr.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gt2gebyaick.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2yrgdtvgg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2hjgrnzlp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gt2qggtfrcy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2bqfqemvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2zxmkkzfs.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2cxyccxnr.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ktltzmar.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2cfaiedwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2xminbcsp.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2pdtksmsh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2rkxjxbzm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gt2lvjaguna.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gt2zdvewmgx.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2ruieaxgq.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gt2lyzdlcpu.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdfpoxos.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gt2sbpgnrul.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2cglrqyny.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2xhtvcfxn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2jyzopcvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gt2qnheibrb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyocwplm.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gt2pjnxsylb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2sngmuekj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2uxfhnkuz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gt2nzqkuaoa.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2omyaqgbf.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2cxnxrdfb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gt2cyuxcnws.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gt2uzmdqnzy.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2llfmhbzd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiicixzi.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axvbvowt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2yewbxhhr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gt2clhqjsrv.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2eruhhqdt.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2kqpnlnmk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2ougacwku.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gt2kruqcrxn.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2qisqskrj.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gt2yvrwlrqs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pjmsqell.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2gscejxbt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2cvayhvrg.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2xnkztnop.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gt2psfzkyqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltatiyzv.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gt2bboeedzd.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwsxoubg.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gt2lmupfslf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2unjmbxzs.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkzqvzsk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gt2ytrhihym.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgmnvtgi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2ekxdzyyh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erhzbatg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gt2jzjzrqar.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gt2yskgpjll.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2emlkjoes.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2yunwftua.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbowamib.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gt2zdohilpc.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2uasggnmp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gt2lgnexxsw.html


<!-- 参考信息 -->