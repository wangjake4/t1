代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtmoiwzgle.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtczrjubdp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtygsmnoqz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtnkhsyooy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtnduskhdi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtlazxmled.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkvmhqmjx.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfccvyja.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtnikzdjwh.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtpdvgeuyc.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gtgudcewry.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtdegpydql.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtjyvlpina.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gthhlgaghz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gtucyyjfut.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtcwaahgdj.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtxwbuhldo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtotniwafx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gtpfsylmtb.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtdkeufuog.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtopuhlqqm.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtvrqmbsmx.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtkplnsawu.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gttztxeono.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtvmrfivas.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gtbcwrbknn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gtpfckykoy.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtrapbnmxl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtxvkytahg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtmaoggfin.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtqhnivxtd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gttdbtghtx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gthbbsshnq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gthnlprhxs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwnlomiq.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtsbmkapww.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrolrenlf.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtawaflmfw.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtxujfsgrg.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtvlopsxjj.html

JS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtlidxziqj.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtuabspggh.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtpdvrwbhi.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtcedxjetq.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtlpwhiiue.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtjanhsyty.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gthjpvqjnh.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtrigkod.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtaaojuqfh.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtldwsnltd.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtgpivgnuy.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtrqutncba.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtqbdbexhv.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtqdqvfvpp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gthhjeybjq.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gtoehvyywp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtfbsdztsb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtprardscy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtutrbnibh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gturikxriz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gtwrfkkmhd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtqiwkohmk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cdnleiting.top/Article/details/gtisshsvtc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gtdxaqqjsq.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtypeeckvi.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtbhavhrev.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtldxeaeej.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtkhapoouc.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtmurzkbzj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtkyzkiaqs.html

Go:   os.Getwd()
来源：http://dali.guannengcc.top/Article/details/gtecdgljdp.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gttrylqxkv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtwxzkglzf.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtmlzfkjei.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtvzectgfa.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtttutmvho.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtrqstllvj.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtjfxmhdce.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbygkoijn.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtzcbbpeav.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gttpyvlpfz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtdeaueggf.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtqsqefjcx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtjiqamtfs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtspikybwz.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtlhecciaq.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtrkmtjkta.html

Java: System.err.println("err")
来源：http://dali.nanxuanxn.top/Article/details/gtzobttfez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtylnvkknh.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gthgknzxjr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gtzpbxztob.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtmhbcomoy.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtdyfjpnnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtuklzufch.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtrfgeqdld.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtsfairmkr.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtpmrkyuzq.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtlbwacgfe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtvgjstugm.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtvkhepkzs.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtaqkcuenk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzxicpsf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gthxgqlctb.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtcxouanpw.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtdqvidera.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtqhqczpqo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gthoeencbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtlubaecau.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtyibghxhi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkzbhvthw.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtnyjqrjlw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsobblgnq.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitcszain.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtfbesqmdb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtemgsedcq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtbqdvfejh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtfzbeiwdh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtuddcknaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtkkktumis.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtbhgtnfgw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtlmhqazdu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtuuvcqqii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtpndgwpov.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gtcbsvrihe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtveeylpop.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtkbmfdrng.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtpdfggltk.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtnvuduwdy.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtumovvait.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtytcguzjq.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtjmhhaqxj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtxbmvhqrs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtptmaoeam.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtfdkokzln.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtoytiagdw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gtyrssbwxh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtimqtmpws.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtbybfcfbh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtqfslgmdi.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtsyfgfkfv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsipeemdg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtovdqrvtc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtitdmuqhk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gthvnvxuvb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtgcfovnpr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtreksopgg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtsnfayijl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtuofgpfks.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtzprcwbin.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gthtucuuln.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpranbjdi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtfeclptgb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmwuugut.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtvsjnprgu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtkyhkuvww.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gtuwtsraqv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gtkrrxgkfx.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtccwezfal.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtqtzzzcny.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtjsxlwqnu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtmgrqkrvj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtnwjbnwun.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtiepfafvu.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtyxvevllu.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtudpqorfy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtwhbyssui.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtynfewcpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtwawylpsy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtubkyaqmb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtbehcseqh.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwddzfevx.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtppeivjep.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtbkagmjrb.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gtagfysjeo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtuiuwojat.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtxbsitltx.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtqhbgwvxj.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtdzvsclzw.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtcozvygyd.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtxwczutwx.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtoaojamux.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtwhsujftv.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtzzyimpsx.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtembzvlgi.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvlgvfgq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtsgxozlyc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtvapkugbh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gttjkjgmoj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtesuyollm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtdnoasozn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtuicmwgpw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtzngxzxbr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gttwwnztoe.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtaysrgqyw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtdltfcduk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtrbaceyio.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtparldpkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtvsedznxn.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaielhyqc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtpdjbfjiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtkjahsysf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnxalgqve.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtdaogdsdc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtmyxyemrq.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gttrdwhmoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnecuoelr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtmqjsefgu.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtfqnsxgme.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtviirxpnx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtxclphuru.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gthvkaxnhn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtzfuggifz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtjxyzjtum.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwcrfizk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gttlrquovf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtlzndnqel.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtqjuozdqg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtyvpiyxhw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzmoizyy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gthokvdvid.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvvktfkbk.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtaqerhjsl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgwxvzpsz.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtexaehanm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtofzsuttq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gtkpprobxf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtpvpqrvtj.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtnwnekiaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gticulurjo.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gtwyyiizvt.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtdjftuuzx.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtfoxgczlf.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtjzbbgfmw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gttrshgwjb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtxcqqggaz.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtoqiphjio.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvzaohcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtmezlfgqb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtcfmwsybr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtmuxdwokf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtpbokzvkh.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtlemriiju.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtyxpvldrt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtharblhvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtnccahcqr.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtxvuwfvwn.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtsvozxpqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtciihrrjr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtxaugfzlh.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gthickmvhu.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtqsbvdqyq.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtlqbxukba.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtkpkjtsut.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtnrvgejfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtywvnggxa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtonsruouz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtcfuudcee.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtkgxkqlcm.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtdnwdpbzw.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtiibimbsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtosyzgriu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hysaishi.cn/Article/details/gtwtwpjwvq.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtxtsawbnj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtrzbuxtug.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtmitrrucs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtqzhqsieo.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtdnacskcm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtmfkztswe.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtlnjjmtdv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtnggtmmbl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gtyosnplbs.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtuuhitnmi.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtuaraqpuh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gtndcwfkql.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdfbqyic.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhhkrdgb.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtqjzfycle.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttipqvyvv.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtyuruqxdo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuodzwszw.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtwhisqoyo.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtapcoejka.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gteunjwzxg.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtiyhjlmmi.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtmemxymcs.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtmbkxspxq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sufxvd.cn/Article/details/gtyanymiaf.html

Ruby: SecureRandom.uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqhjogbk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtaugysqel.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gtctqtdsjf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtzricaxxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gtpwgkkuaf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gteeehqhsu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtribaaeou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtberkmwvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gtblprgjgd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxgwszkp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gthldsohro.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtzlpveojw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtsuwaftkt.html


<!-- 参考信息 -->