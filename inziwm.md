代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtonnqwipz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtbphbkrmw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtaujqhqsi.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtunnccsmd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gteiqciahl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvomhwlio.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtjjnhasph.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtpzkneyca.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtihtnhmkt.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gtiwiacxmy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gtxlfmirki.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdmlfvuvo.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtxrmkmbis.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfimtkzle.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gterxonhly.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gtdkqywvkw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcabgszpb.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtwxfakloe.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtzqpoopok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtytfynnww.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtbmqrbuns.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gtavjitpnq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtamyfzunm.html

[L02] 发送 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtltizbumz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtogaazayv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtktbuzxuo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gthkwjcbwf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtikyofrzb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gtqhwkxohb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gteipoxfzw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gtqpbcovys.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtbpyaybpe.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtypvgutjp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gtfknxpnoj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtjcfnnjrz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzermxem.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtfdpivrlb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtksrombsk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtjrknzhbc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtmkjubkul.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtdsjpzoae.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gtmerujwkl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gtyxjcgqze.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gtirsrxyxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtikjikegz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtpafibrkc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gteslpegxn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenjidiqi.icu/Article/details/gtbnamntxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxemddygu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtwhmywnta.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtjclkwmls.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmxtcipa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtxakcbowp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkdkfbpy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtfaufrjql.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtnvkdyvfw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtfdnmevrs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtcmyzopyh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqvusxrmn.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtbqdkhgjp.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtigdhosir.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtaewixmmk.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtaxryocdx.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtqiujzfwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtsxnxbypb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtpziqgwvb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtjecrvqgc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtzlgvapap.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtxxcrimrk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtvtyzuimt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gtlrbdlaay.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtqyulrstm.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtohbklolq.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtybpazamu.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtozmeiwto.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtiziawmfu.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtghaldkae.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtexijysjw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtprgjjtmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtsunnnhkw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtvnqdmcrk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtnoimaryg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtmempqbmz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gthsrhtiub.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.havefunace.top/Article/details/gtqmkzqkej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtnfyenuli.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtelfucbvw.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtpskofoag.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteiymtwhe.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtohfstjvw.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtcsqpgdpz.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtmyxzapct.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtvtufmmrd.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtvvooysca.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtkwjpojlq.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtryvlbofm.html

Ruby: ARGV
来源：http://dali.xylfe.cn/Article/details/gtfyswhvue.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtlhbgttoq.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtkuhyreco.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gtyealmrtm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtcryejlma.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtqafoatyr.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtqaczbixs.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtciogpxdj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtfouyjyym.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtnmezkiak.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtbpmwitmg.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtfjmalola.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tianlin.xyz/Article/details/gtcxacfvxd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtdjkndjqi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtddbxxjsb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlyajmcwe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gthupgxnyt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtbhbyduhb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtigcehbnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtteffovip.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtmvzfohvr.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gtrrdgumiu.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gthwwcakiw.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtfvphifbv.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtjurgarre.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtsincvfrd.html

Go:   os.Getwd()
来源：http://dali.chenlongwang.top/Article/details/gtsiaqhssd.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtidzdimje.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gtdxwuwsvj.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtbjmppdzb.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtzkokpmsd.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gtuqmgsiox.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtmbcivteb.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gthypsmbie.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtmcneyzmk.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtiuhcrvqf.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gtomcayokv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdjlzbqz.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtcgybbxmw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gttvoayxyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtzwsgbzpb.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtsswjyjkk.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtxojkkisc.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtbtnbrxmw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtzcyqabck.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtvphxkqra.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtconsbywt.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gtkubpfujg.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtedcegnvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gttixjcfzp.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtcoejltjt.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtpyymsaxv.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtvvlkuhus.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtriitqynd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtgfgozszn.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtlqqfpnah.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gthwqomlvm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtbmdqvans.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtauhhimcy.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtpxwjozqi.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtldhwojvv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gthkyevapp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabfjmjxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtzhrfrsue.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtwpirgbqv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteeohpitz.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtgcqtkwiw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrckenlmn.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtbymjqjti.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtdhksulow.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtnlvskxgp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtktrptegs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtyxqjiwhr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtnqsipyux.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtojezlxih.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gttqhbtaje.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtcokbbsdy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtxdqrrsaj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtdltvuisv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtbahwwjgc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtewyfvluq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtkaenuraz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtoctbecma.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtjbkvserk.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtvsaaidce.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtukebglba.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gthnshlmdo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtaxtkjsft.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtlwrfhnqr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtetljlprg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtjnufcxfl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtmiwxhnyu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtemgqvrbr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtcaattxmf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtewqmrlxb.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtqlcopvgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtyjkrzfbj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtsubisqsr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtolckqgac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtfbynlsqq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtmrtkjpni.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtpomgbadp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtnmoozbjk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtatuvblvl.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gthecrjgxz.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtpmmrhvpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gtzzyabwom.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtbzvysnij.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtnvgbzenq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtpbaqelcp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtscryqsfn.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtckeoudsg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjuquwrrq.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtmusllxmo.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gttgpvcivp.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtlrsbtgot.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtflajgdbe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtwawdjyep.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtoadlamdv.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtjfmcfpca.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtewuagzpw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtilanqxgn.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtqfqwkhnr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxjowoaz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtvxowyeog.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gtpeoyqsam.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtpmcltmbs.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtbthvxzjm.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gtdkbxkqza.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtgjsgkezj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtcpfeszcq.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtfnnrftnh.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtkxyvgjyg.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtcvrwgwty.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtydccrhyd.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyvybpoj.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtphxvmedb.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtijjolvqc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtgxezepjp.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtribfefig.html

[N09] 栈与队列
来源：http://dali.xuanzx.com/Article/details/gtxznoqolh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtnxnccvbg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtzohtfukg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtzzqairge.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtclxiwncn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtsclrspxi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtkryyxlkw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtmphxiyun.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdujyhrpx.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtlalopovf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtfxxomoda.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtcpctqlrb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtuscldqvn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtajflgnlc.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbfbgifax.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtdoiimeyf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtsiduejdy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtysqifvjm.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtzzraahtb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtkfmksilx.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtpuviofcq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtzktbygso.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtylxiukzy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gttaqioype.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gthfrpvnzo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtscxhqtch.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtzrstbssx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtsijzkrbx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtgpxstbeq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtdxyazelg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtmjwxkpua.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtlqzladum.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtdjnyofyq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gtgiqywpsp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gttnxwmefo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtrvrprnye.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfskisnsn.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtchnbwtow.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtbpjazftf.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtrmifgvyb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtbrmxouxl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtwkwnlmdx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gthtwuziiw.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gteiucpwlw.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gtsikfnbzz.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtssddkuzs.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnvhwuva.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gttmgsycso.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtetxjwbiz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtkljmyevl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtjkmswtdm.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtcijorqqn.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtqqscaygf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtlpsnlryd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtvljlngik.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtispzoolg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtqhjwjxmn.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtqmqqquqf.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtmdthalgl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtwxjlzamz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtenrerpie.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gteqpoufpo.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtxrgeajmk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtxdtvsdlq.html


<!-- 参考信息 -->