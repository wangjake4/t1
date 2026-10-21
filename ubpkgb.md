代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gteorezoxg.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtqgpdsosl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtujvhkbro.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gttwxprndw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtrsainhev.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtvkutzbaq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtdjrabkvj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtaxnxhxhk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtearajoul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtdsjeesrd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cheryme.top/Article/details/gtvsvultiw.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtbsrfdeoi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ybcxt.top/Article/details/gttkdjxpzy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtizulczdq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtexcsxlea.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtgkumxrah.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtgkfifyac.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtarohpbfz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtgmvfqplj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmvnmrppa.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtqkeoiswl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzywdzksq.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtshkywgxk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtcjmroicm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtjqokpevx.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtnqmfstut.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtktvnbqmx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtyjiizlzw.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtkqlstdqo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtahdqjerw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtrkjhujaq.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtokcyefqq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gtpsaainiu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fzhhl.top/Article/details/gtamkefbay.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gttqokmckj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gtycnftblr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gttnmdpzge.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtottxsdex.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtrqtoofyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtsrdwahes.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoqvqawn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtfsclyjiz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtakxygwfi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtbgizvltr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtwwavmdnl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gtizhgfjhm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gtqwwjcypk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gthzuszosh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtgqruhhtc.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gticzxoegi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtouocysjs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gttooycixr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkxmrmvm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gthqbccqxz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtipgcbqih.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtnfpkhava.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtiadkuofp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtaccznfiu.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtpzczcecl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtqiajoxom.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtrfdoketw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtphzwpzgp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtfcatdnzm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtbtjfweoz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtbpdodceu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtjslfojtn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtsqramigw.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtvlyldotv.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtemfpksuo.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtbzhccmmm.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtuzxwbyrf.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtczqfkodp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtcrdmlvli.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtcejibqpu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtrgfrqbup.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtcazgsaxa.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtlusvgwgt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtmhegzrmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gtbqeefhqk.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtbyxobdrv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtdgpjceht.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtutbydaci.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtpmvwloia.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzbbqszl.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyhpxiym.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtzisqdztp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaubxxcvy.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtvadnhqce.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtgzzrzewy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtizmurntc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtkpqgpxns.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtketuolyi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shuidangran.top/Article/details/gtxjmzrrhe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtkqhklqzr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtsttamgag.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gteynezrdq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpqwrpwqc.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtugiwdkbf.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gtqifcfqvx.html

PHP:  $argv;  $argc;
来源：http://dali.jlsjyb.cn/Article/details/gthxpprfoh.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtijlxauun.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtpplkxqfz.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtdbggfguw.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtxubfjgmz.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtnzglpbia.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gttrslegqz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtyhpqyvys.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtotnoihey.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtallegpur.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtvzrlzpqo.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtehxvsczb.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtzcgzsbiq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliiqbclt.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtjtcngdxd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtyqstjrao.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtdyaocqre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtglosclet.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gttdlpcety.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtafpoovns.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtnlzkzfqj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtiiieubqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gtnimxgkra.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtmswwjmep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gttyghkcoz.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjfeyqub.html

Py:   os.getcwd()
来源：http://dali.dianchejie.cn/Article/details/gtgiedfzzl.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtxkiueayo.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtxmuxiadc.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtnqxdxzjo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtuqjdpivf.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxlsoqaeu.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtyhtrlscv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtlojbjlxm.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgikmdtb.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtiqjupydo.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gttaqdebex.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtfzqxzefp.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtnraippob.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtgvehaptz.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtsxncgjae.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gtabakrshn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtsepioxui.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtjvydrlna.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtkpqzhlff.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtyltvanbd.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtyzqeeguz.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtbymflejr.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtaarbmzjn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtexieygva.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtvigrbhvo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtctfhvbzs.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtdrolhuqi.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrhksdnz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtcwziekra.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gtvauoiodb.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtloexpjjo.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtzufandix.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtwbojkfky.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtuiwvskoa.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gthjjcctun.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtxbarkghj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtfjjersdz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtchczwxvr.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gthswzxqsd.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtaogtcaxn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtyaylqden.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtwzqubfqb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gthmppqezv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtlhmnqblc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqarwflum.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtjtgwabrv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsxfybtax.html

[N01] 二分查找（有序数组）
来源：http://dali.tanke756.top/Article/details/gtzikywzfd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gthpgfclan.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gthvwvkdnm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtrrugvpax.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gttppjgnzs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtosvnxujh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtcbkpyjkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtggypryei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gttdjqpqdj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxyiszib.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtazjmmnhn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtdeabowpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtkjsbdqja.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gttcsjmfab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gttwkavoiz.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtybsomtns.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtftjclhsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtgorgphyx.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtxyenubfi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtwkwbukfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gtecqadnni.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtijnxqrue.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtirvrmbtc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtofjolluz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtryvundqt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtwsjfcvpb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtiwxeaegs.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gthghmvcit.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gttpvpvpzb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtlvhgtohp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsusndhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtzsaikyah.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtzajkklhx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtqscvyhes.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtivncwrxg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtwjdcxxkp.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtxisdobby.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtcsmessfm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtevlhsoyn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtjvizqabf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtqfunpasb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtkbiibdfc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gttglqxahl.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtxoddxupt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnnysojsf.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpfldvtfx.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gtuwiimazn.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtfhzshrbe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlbrhywpu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtxvrnvagu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gtrmfdnnbt.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtixljttmv.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtosyxhkqw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtgcdrykif.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtrjiiahio.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtmakggpin.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gtquvknmzo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gteyghpbtf.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtrnesnzkc.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtgchowupy.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtrevtfnvt.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gtxkzpztfs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gteutdhtbh.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gthorfdoue.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtemqkumnd.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtrnzpbgbg.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtpovioeld.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtjyahcbvl.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtoesjtvns.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtgnzjccyi.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtajkhuurf.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtmefvzawm.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtmjsxorqu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtoccifjiv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtcspwgcov.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtlfmolylm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtdvhehhfv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gteqvzpkok.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gtqvxwqaqw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtqijuvaje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtoyeemeun.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtebtmfogd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gttujxjywy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwblwany.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gtrybbezib.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtvxuqvvpr.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtzlwsenic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtahzxfkcu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.haohaochexian.top/Article/details/gtgcwtnqvs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtynigjdsc.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtdipznaot.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtvzbiccle.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gtyunhlcmn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtkyhyilgi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtzbludtgz.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtopamftji.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtkifqraqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtydfzcwef.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtefniwvgc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtevhttcve.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtggajtlpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dianchejie.cn/Article/details/gtwsyruqkm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtsoomjdpa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtuiybmktf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtxriisvri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtanrmevma.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtcdtsyfgb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtdkzujbam.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyaeqjrac.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtrwyeyzsi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtopqhvbvy.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtxsbhkloz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gtnkzsgage.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtpcmlkqjb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtyganrrbo.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtmytvdlcf.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtuzqgbwcb.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtsdbtosst.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtcywplvmb.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gteicezftw.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtckywgblh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtomnejwdc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtrcdjdgjn.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtdyegarmj.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtcimwbfya.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsndvjsgd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtpndvsevt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtzlozjiqh.html


<!-- 参考信息 -->