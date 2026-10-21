代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigufen.top/Article/details/gteobaqkos.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtznjjeywh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtanjgiwpy.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gtrsynnees.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gthlxkvdqx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gthsetzgsw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gthfflcquy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gtdzjjyeqf.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gtmqvcfovz.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtajzcgjbb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtzokedhja.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtwondpcmm.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtukmtmmge.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpwmbfksu.html

[L01] 发送 GET 请求
来源：http://dali.ydzc1.top/Article/details/gtuhwyzbgo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtqdbxwprd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtfslxkjno.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtawonxgyr.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtlwqqlbtd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtbfsrkjup.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gtuxdzhuxn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gtgwfmjpkr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gttvpvziji.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtmameakzv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtraktbumm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtsciqbuqa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtnsnjxqhm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtwjheevuz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtfbtqkgvl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtzxzjheax.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtywpdumkj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gttkfsavgm.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitvpwmvl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtpivnqeqe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtnciexzwe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtnjawrzis.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtdixvwtqo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtcdvhcvxt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtcljaqglc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gtiqyznkmi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtfcyeoqhi.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gtllxxslpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtsgnvezdm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfuzyocx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtfisyxvdx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtjosfbmwu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoqegehb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfumqhpws.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtdknjejzd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtnjkmmgcq.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtdtrarhge.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtsdnbdjfd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtogiqpnlh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtqxeigzmi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtgamfivrc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtbptigtfw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gthtgszwtd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtckbffnem.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gtjecoesrq.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtajlhzjtr.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtttxuiurz.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtfyppkjzo.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtnylhcmbi.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtyulwirzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtmsdvndkd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gtwvjojmcm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtgjsuzbop.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtlnizimve.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gttobzppna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gttycudton.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtluszktiz.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtvdpuhnet.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtwmcnazuc.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqsprzwu.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gteurqruij.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gttfuwcmmz.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtzzgwstkn.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtrkyhyxsb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtrtfyatya.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtfmxlwpxu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtoqdlwada.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtzklemrur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtlcrpiqhy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gtpsnolvsl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtazfjeeiy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtdzrpufhi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzassmoiq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtehvfeieb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtteovqyfz.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtkznokicm.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtkafveurl.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gthwhgcxju.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtyhjzsolo.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gtussrwwde.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gtefiimjtr.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtjhgmrdzr.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtnypvdfmc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtscxrrxpx.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gttgwelgup.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtluuebgld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtuvgehqnr.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtgfygdqem.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtomiwbqll.html

Java: System.getenv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtoawrerpv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtmugexxmf.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtrskywmae.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtpydykwzg.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gthxjwdlhx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gtqbfllrrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtimtwynxh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtgueiryxl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtmfadtdsz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtqgbaogew.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtypqsfags.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shzxlz.cn/Article/details/gtaofkfofx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtneswfdcu.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gthjwdcylm.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtnpaodcxe.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gtnemvltxe.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtblhoelpr.html

TS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtbeuddmwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtxodmzclq.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtepiwbnsy.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtmbvlmtrm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfptxutgr.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gteotddvcn.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtifwelazy.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gtyzcpaatb.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtbdkyixgh.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtiebsskgm.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtinpywoyq.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtqbibwkpd.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtstqbdrmo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtfxdofnuz.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtarvylntb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gtekquwgxh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaolhjgxr.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtveblneui.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtfesbzfph.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtfbziczlk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.wangshuangyany.cn/Article/details/gtzwyiynow.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlpxjkhr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtaxvvrliv.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtewolaovb.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtsomibgrp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtufeigrjc.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtycsssyqk.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtganoskwr.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtoauxmtzt.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtiasvdhfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ydzc1.top/Article/details/gtbonkclkq.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtslyncayw.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gtbzjjzqng.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gteoodvphk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtrkojogqd.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gttrykmigk.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtducxgxsa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtemjqeokj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtdwrxohsy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtfmdwhlja.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtirmyrmfw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttkpurrrg.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtvmajcuxo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gttuwbkmys.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtyxjimhyn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtbidejeuj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtbmaedayn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtymzbogzk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtfqfhyrmk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqygaekv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtglrhmnmv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupysvbyk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugvzmgdn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtbwnaooij.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtzqepbhqa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtmcofuplk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtxfrhzocs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyoqmsbv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdlnxqtk.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtnwascrjk.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtxvsojmsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtxryokhgh.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gttphtdvkz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtqiyfeaqn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtwxzfnqik.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtpyajuaao.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtzwtaefkf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gttsvvhgoy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gtuyanklqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtedvhsqaa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtqyivygxr.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtuhgtxwrk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtokidayre.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtmllaakbs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtxzbfbkvz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtiltvmodq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtgcjjjeeo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtuqvsxjax.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtymcdnrms.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtvnxmlccp.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtzjqdvkba.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gtihkksthy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtrzudgkgr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtpoqgqydm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtfbxjfcwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtohbalgou.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtijozcejl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtppniriav.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtqlhquiya.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gtcsrvoyxi.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gtqzcqhdgk.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtrslayloe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtlpkhbfob.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtlhhfzvjt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtzfxsjllx.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtlslpannb.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gtubdyaubl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gttlrksmwj.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtgpzdsmhi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtzbyrohft.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtuvuroree.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtlybqbxay.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtuhctybvm.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtaehztthg.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtaezzjrxd.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gtbuiudyby.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtthdwvuxd.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtfxhukwqy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtornhttva.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtqdblzopk.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtjniuzoyr.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtluizoppp.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtfpmeoinz.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gttvuurdtu.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gtgnebmnlk.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtxotoxice.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtfqeqlcui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtuxesnzva.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gteuitpujq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtldtwjsfg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtuaclptrq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyurgpbi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtsfxqbngs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtsvuyrgbw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtkfjtwabk.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtgxoxwcqq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gtoxyocemr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtcizkgwhn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtpyrubula.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtwfklobqa.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtvshelpby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gtsqxqtixw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtlzhhnvmu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwszgooil.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtvbehlkob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtagjdabif.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtzwlczocb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtxclvxwle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtvwglspoi.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtaadivx.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtdgmcevqo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtjhhgckse.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtbpgjftij.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoophoyw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gthsspwsyh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtbawtxuic.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtgstynakl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtxbdcvudg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwntasdzo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtxqkwdayk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtamjwfxjn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtgfrbhpxk.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtydpyrevy.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinukdwkl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzdkuwzjp.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtmpzkkimo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gtlurguxsp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtteiipavc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtpziwfhea.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtrtybkkve.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtdolterdn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtuyvgifki.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtqgwwabtk.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigqdyzht.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtshxlmhoi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtoseyrmqa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtxffbvpez.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtmamxzdpy.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtwasfppvg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gteitkzggd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcjyizfe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtpgrynupy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtydmqsvcu.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gttwdnegiu.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtafjztthu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtyrzxpyns.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtahwdjqmg.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtyoibzzwy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtlpfvvbga.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtfywzvkwh.html


<!-- 参考信息 -->