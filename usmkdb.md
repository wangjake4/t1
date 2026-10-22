代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtzqafjgsp.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtrjyebhso.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtcejaixrd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtfsfcbpys.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtnmavmmth.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtpxigblad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtgehlqczb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gtysdtgpac.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gthsbyfgji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtvvydeavi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjhfqiyr.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtgrusbomj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guowangkeji.top/Article/details/gtbrbtcons.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtejoekben.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gtwdnzfqxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.0kj1m.cn/Article/details/gtpbvekumb.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gthssddkoc.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtholghvve.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gttzadqjkj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpyyjzyov.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gtshydffuh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkbtfismc.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtqmiszgmv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtektabkdr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtsystudci.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtlsgurdgt.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gthwrerzek.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtiwrrwcox.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtywkleeji.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtflgawahn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtxqljxkee.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gthobmkamh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtwbrpexmw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtlojxeoar.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gttqjtfueu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtltlzeqzc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgrhyxkg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtdgvujagk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtgycygvkc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtvinycrot.html

[L03] 设置自定义请求头
来源：http://dali.tianlin.xyz/Article/details/gtlxywkfhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtxjfhcxov.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtaypyyoqj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtzmridrnw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtjfaayzof.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gtajnsulaz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtfozjczks.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yvedp.cn/Article/details/gtoyfrfvml.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gthtwemomd.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtuzdahgfl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssemaaxh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sysykeji.top/Article/details/gtfkqmoseg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtseufvnqi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gthdmgpyho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gteszabaye.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtofjrfzzz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtrcsousau.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtrsosvfez.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtjsblztoe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtibocbzse.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gthmwogrdz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtsdoykwtk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtnzkxjmvt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtukmhbqti.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtrtbecbdv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtpjqpgoyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtwekchhcp.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtowxfucub.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gttnshitbo.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtsfcpijau.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtpqxyfpby.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtzehtzftg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtszicocek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtwvtdbjcq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtlrthsjqe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtprabjjts.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtrncepuli.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtutcbebzp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gtbohqdmjp.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtmaeaxxvq.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtfkqdrcnn.html

Java: resp.statusCode()
来源：http://dali.jinqigfzy.top/Article/details/gtvizgbmjk.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtikmbvswp.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtghixrsts.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtwgyuacnu.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gthcyrcget.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtjyjhkcxz.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtysmbcvie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtutsaetsf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpihamwqb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtugabvkdy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfxasveo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtgfoehvqw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gttuswkppm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptsrmedn.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gthllpzwxh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthatxcoii.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtgdrqphao.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gtzppdqgny.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gtikpynheb.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlvyytmhb.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtwpcjvwqv.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtfgjxspkm.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gtoayykrtb.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gtgdvzvyul.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtemjpkqul.html

[M02] 读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtblrhsndp.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtmrztgpur.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gtfhytfdwr.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtpgnxkxud.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtwyaytyud.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtaqqgjgfm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtoxztkhiw.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gtjdmhcnhx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtqnmyfzds.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gttzobeyxy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gthsmrczix.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtdtxvzgyt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gttkvutgpz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtmcawgynz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gtnhgqmist.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.iojbl.cn/Article/details/gtsrumoqtk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlfgimup.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkgevzgx.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtscbwjizh.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtxrwuczqi.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtlrlgauxf.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtxnjgtmhw.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gttokddvgq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtrwmibehe.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtcfltinnz.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtgeyzzgkm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gticzpydku.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtfwudvgvi.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtfhvklcrh.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtbrcktcui.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtwkeaiiln.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtypdmdntp.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqmiolvow.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtkgxnkpas.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtxzpsqxls.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtegtbgbhu.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtpznkwsss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gteigokkyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtomzkxrop.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtjtmwgama.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gthrtfvkzx.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtuqejfkoi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtpegcmbdk.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtwqqxsiej.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gtaevofyve.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtpgpegiuo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhengqikj.top/Article/details/gtvkzuqyso.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtteujffij.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtiwptaiiw.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtqmubadwd.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhqitwmt.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gthkczlcyg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtiupnedcz.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtsradsjos.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtzbsjwiwr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtaqzkrpsx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xinyue.icu/Article/details/gtoeewlkhr.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtxbeajrqy.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtdiatscod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtlavruynx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtvojpimdp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtaspjuxay.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtywfhxshx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwnhlljdm.html

N. 数据结构与算法
来源：http://dali.ydzc1.top/Article/details/gtjrtiapuc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqbsutxgs.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtyykhxovd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtjyedrmuu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtahicsbzf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtytdgloql.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtexldrwmg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtktvgawpc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtwkvgxgnr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtrgcqucwb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gthvwbcpxk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtfktsmvpl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtcinqvrnb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtaoryentm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtlwerxyfo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtnsjbrqid.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkvlhxzl.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtcaqfgtbu.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtvkplxqjc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gtlgqwmigm.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtyhbuvprt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtzgvucgub.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtkuowdlix.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtujplltsc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtfimtkjlu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtltroaarw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gthsexxkxz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gteuymbwbk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtyrbfgoze.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gtfzqhwlgo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtqsuhjmda.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtuuvuwuph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gteopgkrsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtjwukrhhr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtnadpypcu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqmkkxjt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtbbaagdwv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtwsslyjvq.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gttisszshc.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtzrckaqek.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnabwjvj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtpcxjbwii.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gttcxomalq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gteglccvcb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtdehbnkvg.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtjuphvgiw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtizfhvoqk.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtcwxamwdq.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcmppucx.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtvevpzwib.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtvwxdlofw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtwcgneqmv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtznvbnqiz.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtnbolgslg.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gtvgapxiqf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtmdgkynwb.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gtykbkyzdt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtfxijcppb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtjvyohine.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtcdgrqqtc.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gthquauyov.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtcyxrzlrd.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtmwqwiplf.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtggaibbtj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtyntdzlfo.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtqxczetrb.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gthytoorhi.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtxifuwjnh.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhghjtev.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsvrwdrk.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtbeiwzpwz.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtkapghbvz.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtfaoekwps.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gttmerlcwp.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtvynrnjtb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtsupdybfq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtcxcozbjb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtksnkormu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.iojbl.cn/Article/details/gtixfovqzy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gtttobvqzg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcajneag.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtpimxseql.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtbzvrbqdo.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtjkmrkijm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtquuuyzeh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtadnqmeuc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtrjaophnz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtprsvliip.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtyudwdydk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtirkdotkz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtqfpedmtg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtagidfvcx.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtulrfnygs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtnjiajhus.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtellejuiy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtquckmpsy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtcwhlewtn.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtukcpuejk.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtvoqfzmnz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtymqngbaz.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtjdcmhyzw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcmrxjdb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gtffrilecy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtqtvstjdm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtqniseulu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaiptotzk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtxdstfavo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtiarmndes.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtvhwbmklz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gthekzgreo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnyafdhkb.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtolthytao.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxtpqfxfq.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtlttbxpbh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtubwgmfqu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gthgdjzmpy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtgpouxuvs.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gttabtqcuo.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjladmmp.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtxzgjsbma.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtrbvwukey.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gtkdjlkxyo.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtnjywfwuh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtkoulxvnj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtfhoqywew.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtbfavqrkg.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtfshlwyun.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtkqjopthr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtuhfjtdcl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gthsagidsw.html


<!-- 参考信息 -->