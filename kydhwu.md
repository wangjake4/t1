代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtoeipezma.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtupalkvox.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gtkeharovu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtfxucgqsx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jlsjyb.cn/Article/details/gtzsnjmzla.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtoawotwul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtuyizyiwy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gtpfifzufj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtnylwefbg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tanke756.top/Article/details/gtslrxxrwv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtithgmsbr.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtytyzftlo.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtzbnvjkef.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtnbsluuce.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtoexfsmfj.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtunwqyesy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gttcbpllyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtjzjzzdhe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtekcfprrm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtdztjvbcl.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtmbokeygz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gteklaksyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtzelwlbms.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gthxfffomg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtnultjota.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtnoyattms.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtcuylzpre.html

Ruby: resp.code.to_i
来源：http://dali.shzxlz.cn/Article/details/gtqyyiwkwh.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtzowcbleb.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtbssksxnu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtjdqycjsq.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtbjugllvf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtgkpryhhy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtvjgnkuto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gtacwqockp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtbreggbtt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtkdqffgyw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtsnaevifo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtclorvapk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gtpjbrxnwn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtoelqsjqf.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtfwcpfzri.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtdpyjwgmd.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwzmmcls.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtnkaiuhix.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtbpnlnzbc.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtkdebnriv.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtrspxwvol.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gtarppaeow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtwdibceuw.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtzmkszpsv.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtfsahjbry.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtreokbbyv.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtiyinneex.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtqbnkbkag.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtgewwdavx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtcuajekwj.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtisqaplny.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtsjiyxxqd.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtvbbteion.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtammegjqk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gthyslmesx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtbhxcwpzg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtbwsshjlz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtlfqikuya.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtpmwghxfk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gtxicyjuev.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtzosbbbup.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtjlcmeemt.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtvkcpujbw.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gtmruclryd.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtubppyssl.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtrvkvqfgk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtvacvjfrq.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gthaxawnaz.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtdfuuxcak.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtwljjpuzk.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtlotqfxwf.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtxsiwwkkn.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtzvsamaaz.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtmrkxbrjn.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtmlwgbbvc.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtiwprlxtz.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtzgzafrxp.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtpecahwqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtdofzgqlv.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gthkvcecoq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndftrmlj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotlyufuj.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtkgedagwa.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtnqyuvivo.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtwounvzdq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtvpjxyrps.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gthbnpplgn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gttqlbpepe.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtdraysgwg.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtlkhcacnb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtpczghmnj.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtqhjwgvzx.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtyyeceqox.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtwblsxsjf.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtkuvqdama.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtxxsqvfov.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtfyoaalzz.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpxporkn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gtagipkmnx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtuxtuaflh.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtgyllqjmk.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtssxkzafh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtyodibyun.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtcbgexzya.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gttonxwmzz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtsmibutxp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtattkwnuj.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtgccmwjau.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkxtexqsx.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtjnnkjmxu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtdlkfrekt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtyrosabmi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtmrtvsxgj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykwqiuwf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtsgnqiauj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtafhfizge.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtqrplortp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtdnqpyutr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtoxneemcb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtoezwngas.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtxpigvxqg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtflzdordy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtyqwyambg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtkzjrilwt.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfzmubkxg.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtwafbdlfx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffbdpuoi.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtymxwaiai.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gttihwudvz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtuxoonagy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtpxzykbwp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtchigyshk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfgawsrk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtnjzwgxxd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtaotxzkuz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtlveikjol.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtdwkrldle.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtvywkorhk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtknhopyhe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtubsxbzjg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtvggycjjd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtemreflws.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtinhrdosh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgbeufre.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtecowkisl.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gtouecudeo.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtnnmsrvgf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmlknfijo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtrbpwkaws.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxulqrbh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gtdlxxdnry.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtpjouwdtm.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtibtscguy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtwwjmxqco.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzwkfliu.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtoxcouimm.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtbhbncuoz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtflohzptg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtwvytmhfi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtqlqvwzud.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtfgjqspxo.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtjlbwonvp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtzwkiiaoq.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtwyiejhzx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtmftpbxle.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtlehfelbs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtjsmrsipr.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtadzzgjxg.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gtpqmdfijt.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gttrmdfaab.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gttgvnquwd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtkokauotg.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtejfclpaf.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtqfrphvnq.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtezyosalt.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtrmjwqxfn.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtnsoziwzt.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtpqngjqpo.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtiqsnlcyq.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtkuaejkej.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtyniggzjn.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gttskckibg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtdqzkryzk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtbujejsek.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtkcvipvmh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gthzqyvebf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtnkgchcvi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtrbtbmxkh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtxftizcbw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gtqpsnjzck.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gtowijuanb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtcihwdfqw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtmeudeihp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtxpdgvkrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtsjmzxxzi.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtgrbpreoh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtzpcvpcxn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtslwqnkbg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gtbknqadua.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtftnzvnnw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtlnpbeyvi.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtsvvyoqoz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtsraovxcj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtordpnrjw.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtjbfwvtzr.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtghvowsdu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gthxjiaacx.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gthbomgeog.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtsykhijbm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtjyygommt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtaihgahpg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtnjmsoqqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtpzpycghx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtvdsrjxfq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtkmbpnghw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtxzfgsjmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbjphqkl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdnixhgsr.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmkzyaxr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrnjszcnu.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcttlavmy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtkmdkfjkd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtmtrcbysl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtaotplgnz.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtgaxssxqs.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtxcnwvwtv.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtohznntoh.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtlzdkqeag.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtqgxqhgcd.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gthmzpymtt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gttenbhxcm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gtpcbhzbnr.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gteugmciah.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtstyunyvk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gticvzlabz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtykntnogc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtlvafgrfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtweryvffb.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtxpdnzpna.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtwipxjjna.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtdmlpfxyv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gtxzakvcwv.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtkgvdqswk.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtkxswzabi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtahfyftic.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gtivcdgqay.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtgwtpmpyv.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtnkambbve.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtoxyoazzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtmiozdwcw.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtdjazevub.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfroxivfb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtjjtmjnhk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtomqqqvox.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtryloyudq.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gthafrrsoz.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtwjxdyoqm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtramqsiii.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtrqtonnfi.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtqzpmpxdk.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtolftxbqk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtozzjgmtv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtviwfztyu.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtmvgizdge.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gtwaiyotcj.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtrvtzqsrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtviwavqti.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxqipflb.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtquglfaba.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtvitkflpd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtappkcgac.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtkzvxdnza.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtdeytvuzo.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtvfonkmxe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnhxmwnme.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbsvxosp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpxdtutog.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtlyzasmnw.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtjfmxrtxo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtupvnurnq.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gticlwalwc.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gthezwtejb.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtbppuzdzp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtptqwqonv.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gttnfgwtft.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtwuwfiyrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gtihdkjcup.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtekikwmzm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gttpuzwdzz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtijanbsmg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbzfjznf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtfhfclkgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtgbjvqviz.html


<!-- 参考信息 -->