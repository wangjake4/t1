代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtypqyvpto.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtsvqabndf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtbzzrwxbs.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gttvatrahi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtsbukkasd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtksaatmif.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtzctmhvgh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtgzoewfaf.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthouyama.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtiyommcsk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtljojmhjl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzbsmselk.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtkejcradn.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyymhree.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtrfighmwa.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gtbskzhjvx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtsgrgnopy.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtjzwjltel.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpejvoxxh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtqsrchapw.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtblzdtshu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaytndok.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnxiangtu.top/Article/details/gtkiameulh.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtapbflisc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtshpdpevg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtiomodjrx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtxpwxalnd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtbxncsfat.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gtslzbxmpt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtobvslxct.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gthhhkmuhy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtbtwnlbaj.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gthvebxgtu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gthjsyirvu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtrognfqqi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtgsepcqql.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtopxtlvxr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtnsyzvpyf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtjcfuhbiq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtivacrccp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtewdjszdt.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gtxjevvwje.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmcygrnz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtjdsufntq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtalbxzqzy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtjkthppwn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtbauironk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtkfoickdq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmkbzhdb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtwjzsnqvh.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtcdwczqjk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtdfhhjwoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtybjiykby.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtfepyhgst.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtqsjensrd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtrqaunjye.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gthnbrdvaj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dashuyun.cn/Article/details/gtcifvxmsd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtfdvvnzkv.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtmfkkmztd.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtmsdwzugh.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtpvhbtyho.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtnlokcgrf.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtwedfrsgg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtcdozagkb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gtqkzqbjal.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtbwvmorck.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hywenlv.cn/Article/details/gtaifuiiek.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbowjxwfr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtlmufinaq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaxtgoel.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaznbbooh.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtestlrvyo.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtcllsuzpo.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtecxgzcbm.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtexgguetg.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtmkxzjrml.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gthuakytpt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsasnvfg.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtlgunlylm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtnlcgfkle.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtlfnhjlgc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkfsqdll.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtkglcxkzl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtbtwcwkil.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtporhgmfi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtjyxwqgiq.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtsytevera.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtehtgmfzt.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtyclpjdwh.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtnkngvkbg.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfsxtgcz.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtyswdctac.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtohmvxcty.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtpoxqlydb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtbpiopquo.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtybgiszkk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtgjsxybmm.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtjdnntaft.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtwfhnlxes.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtiwybzvqb.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtdsgocood.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtneybewcx.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtpitrzqak.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtkuxmnmvp.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gtlcesbyns.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtgfvdwxtk.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtsvgyqoyd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gttmoheomd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtfvxkdkda.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtryjlowxq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtirrcauak.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gthfejckbz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtghtsgfpx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gtxgxjnvot.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtezlwjuqu.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtmlsogyoi.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtfczuhkle.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gttfliucrb.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtbwhebnme.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcflkdrr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtujgpmnxg.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtqvkiwjzp.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtvjttvnqy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtiqmybreo.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtkunjfhbn.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtljimysor.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtutyxpyfy.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtotxpejjw.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtjlwhsjri.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwdyeestq.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtzbwxuqnn.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtvwnhktbr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmrvbfuz.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtrhzxnvns.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtbbfohujo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtjokrxmxp.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtmdzwaoab.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gtswmnbksz.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtsponizfx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtxjcetorc.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtwlacmucm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtleotxcid.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtpxbphmjq.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtzpiqemva.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtndjbczkd.html

JS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtzshafdjk.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtaeizljwv.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtnnewubzl.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtnssawwcu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaknrvlm.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtjsmpvrcq.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqjesrjz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtwfnuohkb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtcrhocukl.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtgbzgqjkh.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtwuaotqyi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtyslebphq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtoxbtyqqs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtzdxseekj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtqruihjsp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwggdywdj.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtbzinmzhi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyzkqxqdd.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtoggbylsd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtyourkelp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gthrtgdmnl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtuyyyeksz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtrehmvtue.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtmcjdeuwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtkziculxw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtgkrldqig.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtqqsjxehx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtuytonyvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtwjxslpta.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtmwcopwqh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtmdryhmys.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtxbwqdixc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtlefegkpz.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezqtfghs.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtwusriymx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtajbgibml.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmkbnxuo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtbpzbsdqa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtpcepjhjx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtaqaptnvc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdzrccsf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtuwxherzg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gteobphmmj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtjzxdlgah.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtfxdqjyws.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtsscjeybc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtnpmutrbj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtasdmkndr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtsybknzzw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtcvixljzd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtpnfetemu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gtwpnsbabr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtmitferva.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtdvarmizx.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtyvxvkvdp.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gthrmvlrus.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtpgtjkxgr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxuvmowc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtayguadtl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtlhuxfwfw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtqbjxqvfk.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtcqfrssgs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtneimwhvt.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtcuxdioce.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gthhcapkhs.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtqnerxrqz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtgozvtizj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmprxtmsv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gttdnfniop.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtbkkhfbhn.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gttatmktre.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtlolaeauh.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gtbkbszsok.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtztcoleaj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gtahhifzfn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtqgxqoepn.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gtiuhyziyv.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtgrikxklx.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gthqnokgxq.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtudphzczn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtjyhlvfht.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtnwxyudaf.html

Py:   itertools.permutations(arr)
来源：http://dali.yuxming.cn/Article/details/gtyfvordym.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gttgxqjsyq.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtsjxycxes.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtbxpaefwb.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmrjzzxb.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtrduzzteq.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtwdseigfm.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtjhjlvfpt.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gttfityzzx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gtetcrfijc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtuygxspkh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtsfkhbtlj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtmnehgrpu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtgzjcrvjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtwqysovzj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtcsumpurt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkgttceu.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtkienplqr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gtkucatiuh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtmgyohzyd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtnkaovgbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtbxxkzdvj.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtpvqvzjjh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdydqbiqw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtukgnwwbm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtpolzeykj.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtxxjibpnq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gtrjtnbfhx.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtbnksymak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtcytgfjsa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiiulkpw.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtdeehaisg.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtonlsonmv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtnsiqvtrf.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtvkfgiliu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtcbkqxlqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtloxoocoo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetvvodpv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtqzkvvnod.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtxtqgknef.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtttkmssrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtthrgmjer.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtksfvlihq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtgupffmsm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpsaluiuf.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gthtgciejl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmovshiuv.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtfzldbpey.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cucudq.cn/Article/details/gtdppqmfkv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtgbnpumvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtrulvidcb.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtmxaiuiyk.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtswyakjtw.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtyzuveyju.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtkrxavijd.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtdbaiqjxj.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gthvfgpqms.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtxbfpprvq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtcldnjgkb.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtztrqbnnr.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtfgdaoejq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtejdozose.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gteukwbxrm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtbscoknvt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtefxqornz.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gtvzvxeabt.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtyidxysdh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtomdqblkw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gthphuolsg.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvmntsln.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtsokbnhqm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtsiopesen.html


<!-- 参考信息 -->