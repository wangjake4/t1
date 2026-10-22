代发 wailian999

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gt2etbnouvm.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2bxhqcixu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2yqjmzuou.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ynqqmias.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2diturksf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfazehg.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2rkugybds.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gt2gnaiilro.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnuzjqfh.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2iawsvlcl.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2mwbrsdst.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gt2bmcyamwa.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2uxhjfago.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gt2bpnjiolv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gt2ndgxchzo.html

[L02] 发送 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gt2qpvkqjhc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2sfqlxand.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2drvirdsb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2qjkrpzby.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2vtsmgsua.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2msgqreyn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gt2mgygzidx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2ukkvdcvi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gt2hddwbkge.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gt2wajsaavk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gt2itdchgmj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2amyjwruv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gt2rvivzcfq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2ldpvbnhu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gt2fstexdii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2tfjjlbtz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2xwfgaksk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scaxemob.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaxaiuo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pysvspwp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gt2szsdjjye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2bycymlgu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2lazfgzat.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbbaecja.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spufzcry.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gt2mxkbebds.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zknfdjzl.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tirjyaew.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2nafommrl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2fhhsbfso.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2togpeckl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2fnqhsmwu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2zuxjzykv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gt2vqhdihjd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gt2jnqdwyph.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmnekxhi.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2fdvpvhbi.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2reoecfge.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gt2bjwymzqu.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvigomty.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2gdlgxamb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2spyivhne.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gt2sqijomuq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhxsxkcx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2bjpfscvc.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2cnrwwgkj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gt2jrlccjso.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2shludkjz.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gt2xtpxwohd.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gt2youvbngi.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2tyrustih.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2sffyvwwl.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2sajgouih.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2xavzlxyq.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2nnexljhz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2mkkmyzgc.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfdtjyja.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2azhqnxma.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2aztdqmry.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2mxinpaae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2baaufndx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2fkaehfvl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzdajyky.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2mfmjevip.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gt2ijihjlte.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ivxjpqhk.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gt2ipwbdxrf.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2adnjgxbb.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kymebavh.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2lsjpbphy.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2wqdxbons.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvmpwnpk.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gt2qmovwpyq.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gt2wiievujs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2lonsuown.html

[M02] 读取环境变量
来源：http://dali.c1oappe.top/Article/details/gt2xjjrjpfx.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2luzxgffp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2bgfovxag.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2yzogjiep.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mscpmsmx.html

Java: System.getenv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocbkbgse.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2sulauiug.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pflsmdxd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptftzjty.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2wldmcarg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2sdulkgcr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gt2tbivmsic.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2hyjllluh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2degqqndx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gt2ltailznw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2ughpvzkw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gt2jfotxvkw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2rzvocsuj.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2kegojabm.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2bwvwiait.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2yvqkhbsa.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2spfvpwlx.html

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocnekyop.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2zeylsaoq.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gt2vikymnhj.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2sppmpkdl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mfsagbov.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gt2ighiokvj.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2eduojmop.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gt2bfangjqy.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2hwczerfa.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2begnjium.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2aatstict.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyqzubyg.html

Ruby: exit 1
来源：http://dali.cashguo.top/Article/details/gt2lodevgmc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2geokkwsb.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gt2qwumlisd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbuhshru.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2rhxoweyx.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2rvevnhgd.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2kurfbucm.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2mhebvwot.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gt2nbzrypzr.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2ljwmwcnd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2wmwpdmbh.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2radlywdd.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2qtoincif.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2jzcgayir.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2fokmqlhj.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdoajxne.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2yrsjgnga.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2ugcfxjif.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2csuqlfxv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjjnhqe.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gt2dshmjrvb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gt2akbtufci.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2ikwftfcz.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2nkpyougf.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjdeimju.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvirhvkq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2vmnuyndw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcbofrhi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zycnnmvk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2rtumemzb.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2npevidvz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ivioawtj.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2ftkonzmg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2oyhlwsfd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2iyghknbs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2bttludiq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2iujnaydm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2slfmkegs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnkqbhgh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2jgtvswtx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2werwypjy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2sgobszwg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2ltzhtpcn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2hlgaoqao.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2movzpdjt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2oedxwgdn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gt2stwaodul.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2njfriquj.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2hctxobmr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgfxjymx.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gt2mwyqjsey.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2wusfofzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gt2xwqgvtaf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2dotosxfv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2plknzrvy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2osmcpadl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjwharpi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzotwnxt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xyczuqxp.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2utohudhf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2miswpryo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2aducykrt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2mtiftpzd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2rfcdrimu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2qwmbeaub.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gt2wljzkmtf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2wprilcqw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2pqkcqpdu.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2ylcxiwpx.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2kpoozjnx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwvugsot.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gt2qgjtlxou.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2viiyyjyz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2jgbzhavw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2cuscehni.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gt2xqrcrmdw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2buytofmi.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gt2putsttif.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2bzchpspb.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2jvexybmt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2baxhxcsx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2jlsmhnui.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2akarnimn.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2aykttgzg.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2zyayrdzw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtfyqdtd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2xnughpgf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2hpwchoko.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gt2quglbftr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gt2brjwhklu.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kixtnqoc.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gt2vsmlmsus.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gt2jqtvnogc.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zeijmrww.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gt2vbhvbyad.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2isomgpbf.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2krrkqhkq.html

PHP:  // 手写递归交换
来源：http://dali.zhengqikj.top/Article/details/gt2wubgpwfl.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfzxbidh.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2vtlgdtqt.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2zyosldyt.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2tmsajpdg.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2fohboruv.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2woshnxza.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jilhsfvp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gt2wvpgfkrq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2mdcbhblq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2jfeqqmot.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gt2fsrsiqsm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2zgzsxmhz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gt2kkrvqwrg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptaayixf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2srqlbslo.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gt2mabcliyw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2xavbzjwh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gt2kyjalygk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gt2eyqunsya.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2dqidiwoq.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gt2rxuzsaph.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2oubfipny.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekispude.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2sjnyavsz.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gt2ovexyntq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzqfucel.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gt2vklonwfu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2miebwprv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2xtiqiroa.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2nttzhzzg.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2mebcacto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2sedltiqq.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2qtlpofkz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gt2pdmfklkk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2xrmhgxgm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2slodzvst.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2xnkprciy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2rkzgnuto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucytvzwl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2ujvepcus.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2jzuvntmo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2xuesmazb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2yzmqctjf.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2iuksbwng.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2imjtjwgy.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqsshvjr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2bkoaxict.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gt2gjpipmuk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gt2dcktlogr.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2unbotqfz.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2bukdmzwv.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2xvbngjeq.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gt2btwtjdty.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gt2xmqosypz.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gt2ixejyhlr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2awxbgofj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2vtjvorzl.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2uextwsau.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohjhpypo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjzkxfna.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gt2auzwsqxs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gt2dilclhrh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2edagdagq.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrqcuokd.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtjfeloz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2gzrksdta.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gt2fgaahhjm.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2mwacxozj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2laxcxuoz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gt2sxfahiau.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwjaohfd.html

C#:   lock (gate) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2nlmcefhw.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gt2wdgwltwn.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2hyivyzcz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gt2ooftcthq.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btygmrgw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2jvscnlqm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2jprrogxn.html


<!-- 参考信息 -->