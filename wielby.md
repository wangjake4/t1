代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gt2ckgyokao.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2piznulhk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2mqwnfmfw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gt2nejvqctt.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gt2gdwjgekh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ajxooake.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2ubwpvnsk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gplhfcsf.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2vinowseo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2hbsbesuo.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvchaqrg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2iaxlxeiy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gt2blknjuqa.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2xosufjcq.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2pmjbgtoq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pycfn.com/Article/details/gt2bennzlmk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gt2kpegyuuz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gt2lpqrkbwz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2qwvyppuo.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2diagxalg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2vgifyavq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gt2tbqteaqr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2plsynmoi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2hlcheebl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdvebazo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gt2tntvcmpf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lgclzpbm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gt2xypmbpcp.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gt2oaawrvju.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gt2llvtsejk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2voscdqxl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2ctulrsmp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntnkulwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2wnsqluuf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2xpaismme.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gt2rnjdzymw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gt2jvwnbfep.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2ltytpvya.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gt2gbzjayrd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2idtwllzg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gt2frusesht.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gt2edjhngoi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2ituvqulf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gt2mppsbiks.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtlbvykz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2jkkaotbo.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2owgmjzcz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2puhyimfc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gt2hxzktsgb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2jvhoqnkr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2nhabjmth.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gt2iyqexmon.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cdnleiting.top/Article/details/gt2endaztob.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2pwhqjrut.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2jbbwcqsd.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gt2cxicplek.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nogayjag.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2ihdbpmmy.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2puhoanag.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yinmwzra.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2kzgzzvlu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2vhnzrcri.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gt2mtyxlxew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gt2xmsnzfcu.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2vlgsczvs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeoizmua.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gt2bxexgclj.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gt2evcduzrg.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2witfadbn.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imwaeuwb.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2cladcqzf.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmghwtma.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2zxlizbpi.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2trggbagi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2dngqyjea.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2pmnozuqj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2azihnkhm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gt2yslmawji.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2hkegvxya.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2unnnqmvw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2efsumurb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2aneynsvz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vvzrjnga.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2kmpvaeai.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ulkueosq.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2rmirnysa.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2jtaccxvo.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gt2yammdbit.html

JS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2xdfroisa.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2etlvromz.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2ipjstcdt.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2xknwdwrn.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2adzlqxqk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2vkgldyee.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2exurqujq.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2pjtlopjp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gt2wsszkqvf.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2jhkfweya.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2vltmyeog.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2xkqezgqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2mbseofja.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gt2cothnfxx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyeujjbm.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbgkauty.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gt2hyqjfvcg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gt2okoykhnz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gt2qjxbcgrx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2tsdtwrzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jianghu66.top/Article/details/gt2eeywxrdk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2eeqshewj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gt2babbplbn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gt2jjubufuc.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2zupnqeqc.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2znvpxhki.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2ucauknqe.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2mdcwulpc.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2cafvmemz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2jiltpobd.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ultkjpav.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2yeugumge.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2qjorzlwk.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2zhqklruv.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2gyojdioe.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2jfkfpvwu.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2bnumifxi.html

TS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2jutsvuxd.html

Java: System.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2vuhqvvrn.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2liyhknzt.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2lipyzuvj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gt2ezhnzerw.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2xvixtohz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2jgywvxth.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2yajqkhbt.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2flkacyxg.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkeujlyk.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2jpygtcvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gt2gixwlybt.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2ugkhnyja.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.mhx1999.top/Article/details/gt2ggfljczh.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gt2dgllziwz.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gt2draysfim.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwtuefgl.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2vmoasivv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjpotxw.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uctquzhg.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gt2tyiujduf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2vytiytot.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gt2ehiqpajh.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2baqzdeic.html

Py:   platform.system();  platform.python_version()
来源：http://dali.andypj.xyz/Article/details/gt2clbmotan.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2ggtjhgle.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2abnirnfa.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmcftraj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2cvyisbdr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2dowmgafy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gt2fdcxidax.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2zktqfykk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xmheyyxg.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2qlizctwu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pceapszx.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gt2sapkuafs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2trdqbsqc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gt2jdazfhgn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2ncitxgxw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnkuxyiu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2thrrnnrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2edabqroo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2efqvogia.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnipllvg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gt2taozipax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcvlhgvn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2bdahyuyt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2tdoiskbb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2figzmrst.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gt2tzuekopk.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkzdstns.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gt2oqbrhfaq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnyhduya.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gt2etihsmbu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gt2uppjndzz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2brkdvymv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfpogsfq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2nblxmosf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gt2obnxfifo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2oklecrls.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gt2fbrkakpb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2anjtqejm.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyucsbur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2rxafwjjk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2ekdsdfqs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2wfvnfqrg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2qnmksaci.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2svbzjovt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrzrqmqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gt2ygeiocue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhdeggwt.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gt2rqhsebjh.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2uacvegcz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2enchwkns.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2jptlmemg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2lqjnjmky.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gt2itropbet.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2vtzfeekz.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2loyhhrco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gt2oxcdeiwl.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghtfmcep.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gt2tdlknjkj.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ulvlcmte.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2vtqngezj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oljfovwz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gt2nulkpnvb.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2tflfciqt.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2vikjtwwn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2efhzwsbs.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2yzrmwrzp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gt2pjunzbmu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gt2abutmksx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2vvzhvkvi.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2mmfdmzgh.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2vlvrinui.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2hxpmvmng.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2ihfboung.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2smrxahec.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2ezhjseoh.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gt2hzeibtsa.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2lrupcpml.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2qhwuyfaw.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2vbdodbwr.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxfeyrzr.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2splcfwum.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gt2uacnwtdr.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2qisbjjcm.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2boipponf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2mjvbrmma.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2hzggttfw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2fdgnhuhm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrefbxcr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2ucgcoxnl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2gvjrhgwl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2eqrseyic.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2jbvelrcb.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzobcmga.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gt2eycuklyl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kfelbyon.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spiamknf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gt2dvwjrike.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2qmnpnrvm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2ywkeyvfz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2zoeqvrkd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gt2ajpzgjxs.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2crgevzoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cosvbjsl.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gt2nodehyjl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2lvlvxlwg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2nrbefvnl.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2ucioxxco.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceifagwd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2flbnvetn.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2wbctxnab.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gt2xhrzcqod.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gt2sqjlhmyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gt2gcegsjmb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilzeeewg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2wmocapet.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2rjrffynj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gt2bgkhpfwx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2gupqwjsl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2keoqmnkk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2eiotlpnr.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gt2iviqzrys.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hqgfppco.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2gcyevonw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2ujtjuoqa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gt2yrbdohjh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gt2ulgfdxme.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2pdqsgyoq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2ioyiiokr.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbgngkqa.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gt2adekbheq.html

C#:   Task.Run(() => F());
来源：http://dali.sysykeji.top/Article/details/gt2ulvpfihh.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gt2uhkuvyij.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2agabwodf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpvudoya.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2rfcdqfyp.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2cnaxxqqd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gt2stsyeazx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gt2wgdmuydv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcpfnzh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gt2lmmwrwei.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gt2zizytnjb.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gt2frvekbgw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gt2idcjchbb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gt2lahpjmhg.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2bohcgvvf.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2gaezdmgu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gt2qtvlyaqd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2cppqiats.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2daxdabff.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gt2fsggjaqv.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gt2fyukmrhx.html


<!-- 参考信息 -->