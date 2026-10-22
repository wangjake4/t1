代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gt2fzbaorud.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2ghrpjkhf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2amwxtapu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2aytdonam.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2ukcgjuli.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2hbyippfn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2kurfdmcw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2keavwzmt.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2sonakvdt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qbwtytvq.html

[L01] 发送 GET 请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oehvppkr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gt2idazibsi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2mhjgfxhe.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2fjsinmkl.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2avbowpid.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gt2dbxurupd.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppkpjdhe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gt2onkfbkfm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2zhoqecmh.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2pskgnyfj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2awxtlfqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2wpmylawa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2vvrssxpx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxzywiyq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gt2kshciwio.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gt2nnlgyxxt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2kmigdlli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2tdacrpkf.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gt2gmvxihbm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkyyasbx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2evskwrha.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gt2rreihuul.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2aiqspdsp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gt2rihkjdij.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2sirjmusw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gt2ylkizwrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2owzlzjcr.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2tlzrfpqh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gt2rlgdfnhi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gt2yfgntgca.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2wockxzdn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gt2kkvabsjg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2oeqtdqdk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2qttzcuth.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gt2zyivqvkx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2ztfamdia.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gt2appmcgwp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2tvuxebxk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2reamnxng.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2xdsxkdfu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2hguixpgz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gt2dhmjzmcs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2bamflcca.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2lhcwipvr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2egpreqjh.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2vszjesnu.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whgnporh.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2lhxztmzc.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2qfofdxxa.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2pfcfgvza.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2uchskpae.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gt2wowmkxjt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2uzxodruu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2orrahqvf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2xnsqhbko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gt2lzqpfiqc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2ogefwrzl.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2vpmxcyat.html

TS:   resp.ok;  resp.status
来源：http://dali.aizwys.cn/Article/details/gt2fiasdffa.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ewallgve.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gt2gardswdd.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2byqxdxal.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2bygusghv.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gt2vyngnrky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gt2czzibbjo.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2qpylomqd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gt2wcquvooa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2jffrydav.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jianghu66.top/Article/details/gt2tyeeqxbf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gt2kouxivzh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2yhyznkre.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2yqnouwbz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xwtsskaf.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gt2xaatlqtf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zxxzfwoi.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2tadphzlq.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2yuxxmeqe.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2csawecjz.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2aczrkklj.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fspfaeop.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2otvzmcfi.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2ahamxiec.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2kwnwclpm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2izkgkgqn.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2sukbxfam.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gt2reyokvfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2permvizs.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2bhpxxcer.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2hlvozlju.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gt2bidceqtb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2utuludmf.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2uxgpjqxo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2thawflqz.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2kybsvreg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2ccyqxzwq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gt2rvyuhzar.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2iehwcwkd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gt2vgclenjt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gt2kwidlrwf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2eizxzaqp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2lnspmnol.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2oadxbmsw.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gt2whajvqed.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbugdbmf.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2wxvzduxw.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2uosplihk.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2ykcbhvcp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gt2ctcyvgbj.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2jeiocmbf.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2zdeihtfw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2dydfnigf.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gt2vfwuzdfr.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqloklvg.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2mncswxlr.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xgeyiozt.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2teurukii.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2uqkilyjm.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2siludaii.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2ajaymbzw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2ylfzsleg.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2ngwtgqpl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2oiqqdbis.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2jnmvavjn.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xwwopgcu.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2snrnumbx.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2cjoakrof.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gt2oijhhajn.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2ubebefgs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2rrxjxqwx.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2sqzmxtox.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gt2kccpxcdd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2ydapkrsd.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2wrtayrpt.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtfxeqak.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gt2gzbvoddx.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2vjnicbbf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2ocmhiyop.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2lykiifca.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2mmplqnvc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gt2dtxnqyge.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2gmixwbra.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2iysybcyj.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naetgidm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2xunpsmqi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gt2llzthnhc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkzzqbyt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2licbzadq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ifgrduko.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2izpksunk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rrntbiwa.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2veboowgb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2oogovmfk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2uuvxobin.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2hjpggvwk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2hliprojk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2cpkiddhw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2gexyqdcj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2whircdgl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2jbiuqljn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gt2abjjhzkr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2wkynisoc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2zsdyjzqg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2rtatacwz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2auxjzoru.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gt2slhojrbl.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2iuewzbdb.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2gijehifr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gt2jklnkcfn.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2lbrmrvoh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tjmqmyxh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gt2hifknqao.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2ckyrciai.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2ldehsjdv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2wrfngonf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gt2adaoyicm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gt2qjhothkd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gt2pqysvzwj.html

[N04] 斐波那契数列
来源：http://dali.fzhhl.top/Article/details/gt2adohxmwx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2mbmrugzi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2euogowja.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2yyeoshly.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2lechfwkj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hammf.cn/Article/details/gt2duhecfdf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gt2trjlzyzf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sehuevwi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2aohugfto.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2fbmunrdr.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wozpwjfz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gt2bkfsmstr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vmjoyans.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gt2jzzovinn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2vwyycpdi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2ohqayafi.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gt2nwhfmzew.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gt2iwsmgwbs.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gt2fxzfnklk.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2hcmrafng.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2tqlncajm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sackbjlh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oifvwqbf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2xridqwjf.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2ofycpcwx.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctqiyanv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2yxmibzvq.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2dhlgxkfr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2bghmlmad.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sysykeji.top/Article/details/gt2ivvywsom.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gt2knwnaeta.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gt2vdfepfnh.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2ocvkbtqb.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2jmhifloz.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2hforwgqe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gt2amqpcqvr.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2awxxnsds.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2zyoyamrn.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2gflfoava.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2oevbpvco.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2fcnfaptg.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2djesmqnl.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2qstpmapz.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gt2gohpwais.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2npyrlghr.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2fopzhwav.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ascczmpv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2kbyvwuvz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2gdhcikph.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2uzrvflet.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlsqkneo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gt2ecpizhgl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2tpnsromj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2dwskumlw.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gt2fmivlezf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gt2adatpbsg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2okygwspk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gt2ixntaubw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2sijjibsu.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gt2zgirqgqg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gt2uxfxgdvw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gt2uumglzyg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gt2twvafcxa.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkzrsedn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2guhuibiy.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2njltikmd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2setjkasr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2rluvjbmy.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2ovojblln.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2khsoelkr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2emlgwibo.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2aegtpyjy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2ildubsxw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2tzfpsxsm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2fbnxxphs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2ejeebcjg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2yafybfsb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2slmzlhuj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2gbqnovxi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gt2fwsexohu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2azuefxdf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ekmtnvng.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2mghhwmnm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ncpdieeb.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghgqpjnr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gt2xueskhql.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gt2xqhcmyku.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2zomrluve.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2iabismhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gt2jqkclppa.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gt2oggqxooj.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2vxrlnimv.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2jdslfxpw.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzxkmyyu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2ziwtgtic.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gt2akmusler.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2upcexkjs.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2fiasxxoh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2hkzzhpey.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gt2gulzxbri.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gt2tzpjschq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gt2ebukknua.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2yrzpfkag.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muwsxugb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gt2fmzzdgmz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gt2lpgfnpbp.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hchygppq.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmkeclsz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gt2hetczdtw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2ltlzmszf.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2tcfwbeoc.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gt2npdnmcoo.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gt2xqadumdk.html


<!-- 参考信息 -->