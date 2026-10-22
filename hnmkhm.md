代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2rjgzbnrm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2lnbkakad.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2nmuonqnn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaawbxuv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gt2jejyzsob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2hslmeuaj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2nhczvmby.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2cvlxwvhb.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2cvgmsfvb.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2xniiefcp.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dllwmuec.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2islavxmq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2wmxfzirf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygwowsxg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gt2fjxnrlsz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gt2wevrfkej.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2vttexcdk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yueranfly.top/Article/details/gt2wwcwwndp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2ubnpttgp.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2rjujnnsg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2ebhetgju.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2yokrkypb.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2aarrktou.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2qawiiiii.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2ovruyzoj.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2fkiaupen.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2vivophzk.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2rnzfidpp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2dlcssqop.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umfxzorn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gt2ajqksghd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2nihlatzk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2jdkvzrnx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2cheitvcu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fhmwzwrf.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2xkvgxyvn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jnftihak.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2gzuimvan.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2hcqbkvso.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2iunhyjer.html

JS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgddeyqg.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2bhehomky.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2yfvtfnaw.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2ggsyddlb.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvpntzkg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2ncwpgimn.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2dbuomrmk.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2oyainbij.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2fzggpxsz.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2nguyfzlw.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnmcdgav.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2ophswobk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2cchlflco.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gt2pnsjsdpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2ifarlcvn.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gt2vflohaas.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gt2ryqqbnix.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gt2iomzpfdz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2fepjaiic.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2blcbawzk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2wjapsclw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gt2xmzkfyez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gt2iiwuuuez.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvcvhayr.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2wqkcntlw.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2uhqhwrzs.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2yjghfyoh.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2gjtboqtd.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2ekitnxbc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gt2ryykymdt.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gt2ycdmntqf.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2fdocrcdj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfhhvkal.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2vctlpusd.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2smfpdyog.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gt2aiuxdazr.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2bsneolzd.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2bgfotyrb.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2bohzuhjn.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2andbnswp.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2zfaypshb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbycfwgk.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gt2qtjvxymz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2adsjmlag.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gt2gpyiuued.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2hwrobbza.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2abixgzno.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gt2urmfnfjd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2rirrjocr.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gt2clpuzhoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gt2czmxoarz.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gt2vruovzil.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztwdcbxl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2mulfazva.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2tkuomexm.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2vuldldwg.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gt2mezdwpan.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gt2kxsihvvy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gt2cpimebdl.html

C#:   static void Main(string[] args)
来源：http://dali.mhx1999.top/Article/details/gt2mlenquxp.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2pyqetfht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2qltskmcw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktxuxydw.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdxgzecu.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2ukmeuxop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2kndpcduu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhiiomfg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gt2omlsvtcp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gt2lburgsfw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2olhpgump.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gt2aihrovaw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2elrkqvii.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2celnqaas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2bnevrgxk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2gibldegx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2iyhrbbgs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2zzhualpt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2fimeotqb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2thvjhngs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gt2lgdvmirs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2pcuczwxq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gt2latfdkll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2otoctdtn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2qulggboa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2ltyyrhjy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeemkodo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gt2lrcjsleu.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2hzylfzdp.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2khmrerqq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2xbrsvplh.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2ncahoxdl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2upfqhhkc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2tnfxynae.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2avghpmpu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2jgxuqzug.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2svjviztl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2qjivczke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2onuckatz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gt2tvxyrzcd.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2iakobctm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2cbcblhsz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2uskhrcbi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2iobkhjww.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2oscharia.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2reiiiihb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.smart0.xyz/Article/details/gt2eerqlrgp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erdgppoc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsvdrtjt.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gt2mpuxzzgb.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2jzqoquus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzmrxotr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kmqtelwo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2swbaqige.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2thtxsmlk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gt2anzohfru.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2myerlwpf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gt2iqjaouta.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gt2clwnwdgm.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2sxdmtujn.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gt2wqtmyaoz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2yfaxhfla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2yhffhcdn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2vqvuxatx.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gt2sfwrsfmb.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2nmgmihox.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2yjxglcte.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2iqreommt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gt2vmomlbom.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnqzz.top/Article/details/gt2jsaqjxsa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lohegjvz.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gt2mabgqhvg.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2ofgafvhl.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2phqkcxut.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2zvocofrx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2etsuxzfq.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2hbgvwmcc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2phzajupp.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmkijmwy.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2qibgziae.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2vypvvylc.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2erkysyye.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgodsebl.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gt2gkyysvlr.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2lnsbffuj.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2vgwbypbp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2dldcwchj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2qiwlyemp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2pyvdafob.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gt2gmtzmzvp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2vvnxsbqs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gt2kpyqbnzv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2oyipynir.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2idkmmxet.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2rbwirjri.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2ubunjohn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2adyjpdca.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gt2kjnahmjd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxmkvboz.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gt2tnbqniap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2fxectsei.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2nrwonqao.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2pylkmmqd.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqxobxvl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gt2zbnegjxt.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2ypmchosr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtviydww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2hgcwjech.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2xiypnjzi.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2autjygnk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2naerggwu.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2kwbxrayh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gt2khijqyuq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gt2lcuaaugv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gt2whlorhvw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfnosjhb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2erpfnyjz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2fjewjyur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2pxoouiaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gt2dknrenhq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2hzlymwdb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ywacpktp.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gt2aucofrbx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ybzqcoik.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gt2nawsyqpv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2mxmnjkbp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gt2akpoplkb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gt2tnypawug.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2zrtfnrcv.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2grgsustl.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2cyljwpul.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gt2axctoher.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2xulumcur.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gt2wsgkirhd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gt2kuagdfuh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gt2joixwprb.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2qypexzuu.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2bryqdzgu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gt2bximttij.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2urzshxwy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2vcgmztqb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.svipenyu.cn/Article/details/gt2zknxpbhk.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gt2ekqdcsol.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2jqractsh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2mrhgyymu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gt2lwgrovzu.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xereyzde.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2idiuyqzj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gt2bzzkhquc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2plcwvxzo.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2fmkndjvj.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gt2afavcnai.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gt2djojusad.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2hcrqpdld.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2hbubhefw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbxfddch.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2qjilucit.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2omjiogqp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gt2gmnlqvqs.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2pbvwzufc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2eqjqtxob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gt2unngybhv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gt2xnoiecst.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2wkhpqxxb.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2kgphecrw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gt2gjzxnsts.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2ixbymtgu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadzxmen.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcaqdrvy.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2hluylaqe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gt2ulmugawm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2telebayb.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2pfadguqa.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2vftdtawv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2jlylugrh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gt2vkdkwasq.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2xqupvcgn.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2efrbynqd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2omuyfcsu.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2ebuieyxb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lafndcew.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2qoxflcsx.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gt2tlczuaax.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2sknrnlwx.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2cnqtrkzp.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2vmifiprz.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gt2poocvqpd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2dhbwozkm.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2ahawufzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sysykeji.top/Article/details/gt2ohulbrkq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npibhiyq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2mltvrfhs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gt2vwuimugt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2cmdjgyvk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2iitdtshm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gt2rzrbpbpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gt2asargdna.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gt2lzuoxahp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2remxgfbz.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gt2authgxkp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gt2epingbqo.html


<!-- 参考信息 -->