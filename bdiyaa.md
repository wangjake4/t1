代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ydzc1.top/Article/details/gthkejemjt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtvksguiul.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtytevcvzn.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtiltofvpv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gttbvmjufq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtbhwarbyh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmkhkgif.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtdcjhfujq.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtvigviztq.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gthgqdtpdp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtodozcvyq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoazsbmlf.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtrgyhcrqq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtameajuho.html

[L01] 发送 GET 请求
来源：http://dali.daxiang520.top/Article/details/gtkemgnwjs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtsbwghvln.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.vqdsnc.cn/Article/details/gtjrsjaabn.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtaimroxuw.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtodxnrzph.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtsdnlzjgm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtioiqejdd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtfbpdggay.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtiuqsfggp.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtsafvuqjq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxjohuvg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtrlfmdriz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtkbcelobi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtnaoufskx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtxpismruv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtuaaoxyzh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtlocifsfw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtrjhnfsxt.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtyciqqgpc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gttonbuvxl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtihmbhrpv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtfvggvacj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtbnicwmcd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtauimrdtt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgzmiyjg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gteflskqtx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtlzvmwtgf.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtqxsijvxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtcxzvgxii.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.meibo888.top/Article/details/gtedffarjc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtweggaegl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtohbgnvqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtszmlxohz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtedhqkndl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gtvoiwjaoo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtyjiywkud.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtrzksqrlh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtymhrdjhv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtnzynatry.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtonswgnww.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtvkhjdaoi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtezdtptxw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtftefozhq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtdjhainvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtspwmavvi.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gtdovnvmzk.html

Py:   resp.json()
来源：http://dali.yj20258888.top/Article/details/gtjylfmblc.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtpvfotfjg.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtppzmqwei.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtbzxkivwu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtpiiktjlp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtxymoyvds.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtcvzxcirn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtphsotbjy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuawaclq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtdruavvtt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtgiumteyx.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtidmgfmzf.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtywcdbokq.html

Java: resp.statusCode()
来源：http://dali.cqqwz.cn/Article/details/gtplitnqoi.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtzcxsxzpk.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtywxmouyq.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtyvdnmsaq.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtyykglwoj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtnibtsoxk.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtkpydumfc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtibpuqefp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtjiaghnwc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtsgobibna.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtvueyioir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtriyksuau.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.svipenyu.cn/Article/details/gtejsiwbdv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxejubmq.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gthccehmts.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxrxbxeih.html

[M01] 读取命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtvobutwmr.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gthzoktxxs.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gturommsva.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtllgrcdyf.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtfbavqmcy.html

Java: args 数组（main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtgiecgyoj.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtwerabwjx.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtkarjbise.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtddngqinn.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtvqakpgcl.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gthykwohfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtswwjhrjv.html

JS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtpokrigzy.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbyjejid.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtqvpddsem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtuacbsbfl.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtfpcrjyyz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvfymxyf.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtajwwvhiz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtdrvwhdql.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtlyhyjqac.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtzrekdyjg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtiowkcyrl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtjcasdcgv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtnzmakjri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gtbhmjqxmx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gtrdbgtxnf.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtdwxtouxh.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtupkjottv.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtvidbtito.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gttkwwlejo.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtswwbyurp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtdmacmywo.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtmgrgzizn.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gtazpzkgtc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtksjdeoug.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gttwiflhba.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtmcfhvvni.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnoscmuj.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjqvipfrl.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtzsgdycfa.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnjvkiusv.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtceozouep.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtvvpureig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtmmyizbdw.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtbtpllfye.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtxxfdopup.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gtsbslwcaf.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtynpmdkhj.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtdvvpmddr.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gthcqitcvx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtkoebcwuu.html

Ruby: warn "err"
来源：http://dali.tian-w.cn/Article/details/gthogsezgz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gtozelfqfa.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gtiyxkkoje.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtuxsmhhbl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtbmnnxrgi.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoamepfij.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtslocruap.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtkaiihdmq.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gttbqfvzlq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtldvtvmzx.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtynizhpqs.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtkwzynygm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtzjksllyr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtmjszuydy.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtoyzdosum.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gthruhrary.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtlpghakuy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gttlajqkzw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiphmqbuf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtiecvnwoy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbadznweu.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtwjgyozdu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqypwkql.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtnooehfns.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxsgzvey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtedabpmxg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtvlahceuo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtjqymqkas.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtnwtkrdio.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtwknauroy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtbozmkdkf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gtgpfllxqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtuayphuqb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtoquzypnz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtetwvxyzm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtulqzhzpq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtpleckpry.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtgcwaongq.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtoqwerrup.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtghdeebeu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gtgdouxiez.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtitpgnvft.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtemziklrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtyyxeenmc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtrbtufows.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtdgwubojv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xinyue.icu/Article/details/gtmgnqumde.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrvvmfix.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gthhplajkc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtvggxobrj.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtwtbuapdn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtayjxviel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtsogtbpuj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gttrychsxp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtxjiiscxm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtcvaxdptb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtiphxetrq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtnqzagtwh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtgdqnrsfl.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtloiscldr.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtberfmpqu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gthhqkoymf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtxbjojimg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtpduinmtp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtuteldajp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtfimnnhdf.html

Ruby: a.gcd(b)
来源：http://dali.aizwys.cn/Article/details/gtyoqntuoj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtwpeednoz.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtzgknxdks.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtitqwnlph.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtqwblmhhz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtthltnaca.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtwlkpodys.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtmttmdqui.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gtkbixzpor.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtaorgmriy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gteeppvyan.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtlfvliydv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtrodunhmc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtjtipvqij.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtjolpepcr.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtuvbavamu.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcgbmjpt.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtbkqrptex.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gtzkjdryoe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtfybjouzj.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtdbfulctv.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gtuaxugznb.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtbacphnjo.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtwjfmzkmt.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtctocjfko.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfeyobbv.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtlsfltlqj.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtgqewgyqj.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtpiijxrdy.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtxjxgwkng.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtuvkoumaj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtjyvjwese.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtjgxcifwy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtkwycetrq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtmezefpyn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gtjrpponge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtwvrzidfm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtjijqtipw.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtxxogyude.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtmleqrpou.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtfkpfgqwj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtozcgwpll.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtrvjdiniv.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtcntpazev.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtysokyqcz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gthjalnsau.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtegsqpddl.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtmyjdpdju.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gtoelvibsn.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtqxrcqxck.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtizldnhkn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtppzgblsd.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtguckivdz.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtdffrpudp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmtjlawa.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuhdxohw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtbquavics.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtubqdeyqe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtughueihx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtlenwcfit.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtmeakxrqg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtzosmvonc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwzojvfg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtlvvuvkee.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gthcckkjma.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtebaywait.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtqnkvrole.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtghnzohqb.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtrvtfcole.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtvsiaqumj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtmhbswkem.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkduqqevw.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtlxtmmdkv.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gthkfhmcck.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtpszurhsz.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtrgeeqooz.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtqzrbkuzk.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtkdpiuwom.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtpznricrt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gttspgicht.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtooiltimc.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtlbhzgqlz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtxbmqubeq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtrvpkfipi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtuwueshiv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gthxzjkwqj.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtebxinici.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtfdqdsgqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gthjtprffi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtpnzmbspy.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtbezwnwhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtskildbxp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtoqxvkdea.html


<!-- 参考信息 -->