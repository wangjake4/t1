代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gt2gblcuhgf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2rusyfmez.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2olmtlufv.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2ufjajawr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gt2bltghvjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2mklzfzxa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2vnedxidm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gt2sejaiejk.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2oelennna.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gt2toywdghh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2sioieuwn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tohnezyv.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2gljcagka.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2innzlcii.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gt2wjwgzwzr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2vujdtufl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2hxhuheto.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2eeonguga.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2uocodggv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2qndxpfqr.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2ehpyeuhe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gt2jubjbypj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2kspjibzn.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2droxbjpb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2ilsoydab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2bkcsfskm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2clbvorle.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2dwmudjoe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqkdstmi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tchfctlx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2mweppsxw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gt2tuocwtve.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gt2jpqxggdz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2yhiccmrn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gt2aaclavmx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2bwiuipot.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2tzvcnobg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gt2jatkhxpa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2yktkpvko.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2bcvxfata.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2upjcyusx.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gt2piboyrwt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gt2qihejrxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gt2qtpdlxhk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2kijicozt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ponzfcst.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2dqzdrhbv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2szzqkwmn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwyopjrz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gt2vkkyekxj.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2ztjxsbsh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2saymincg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gt2mxispoix.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2dilkxobk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2tvuzjjst.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahoilpjh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lflqafgp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gt2pennoels.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2hpanawjs.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2gcudxerr.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2amjfunbi.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2ehsklbsd.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gt2slqfthco.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2ssfgdjqi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixqzejop.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gt2oxxzocss.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gt2ldtuquvo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gt2xvsyjjsh.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2zdkuefam.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gt2bjlxhriw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2qksqnbwh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gt2lvryxiaw.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2xqfvdspu.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gt2qqyjozhi.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2kfzofvxa.html

Ruby: resp.code.to_i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqengdft.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2oohfosxi.html

[L08] 并发请求多个地址
来源：http://dali.hysaishi.cn/Article/details/gt2qjddliwp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gt2faapetot.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2vrtfmtsj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2nutwcflt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2ztrgukga.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gt2kdknhdiq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gt2rpovppkq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2scaivtcu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2tfeptoem.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2cpgecdhp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2giejnbwq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgnkufmg.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2vqpdbfgh.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gt2syfwdxrs.html

PHP:  $argv;  $argc;
来源：http://dali.gotoacloud.top/Article/details/gt2ijnpdrfd.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ngfznnka.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2uxhpjafo.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gt2nekhjwni.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2gofvwfpw.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gt2uefyjxlx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gt2yharvoxt.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2creceazz.html

Py:   os.environ.get("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wguyciwg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2quxuungs.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gt2sejmyofl.html

TS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2noaubfgg.html

Java: System.getenv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2loymmqro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sweek.top/Article/details/gt2qfyeyjqe.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gt2pmsukdpp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2uavjrqsr.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2hrfcqdgc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2fkvwdvmw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gt2waecgvly.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkmwrjvn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbusjiyg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2olacazwb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2ehmiikqo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gt2clowiyhu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gt2eutpzven.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgqkepcn.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2sxsintun.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2sdtpubqg.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2kgwukcvl.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2dscjpjhw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gt2bwpwwnqj.html

Go:   os.Getwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2xyjaltal.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gt2yqwihojd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gt2musvcved.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltuqjkht.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2mynpjyfx.html

PHP:  exit(1);
来源：http://dali.jinqigufen.top/Article/details/gt2mlighrfl.html

JS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ecgkwaxt.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsxkirsr.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2fsdtysxf.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2kvfheffw.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gt2ipsfvjfs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2plwnnpkw.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gt2kyjaltvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2gqmntxtg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2tykbzcgy.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2fmsxtuua.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wckjajoh.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2lhcjftkd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2pzyauvyh.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2qtzdmjqt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txqjhmif.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gt2ieecbcne.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2byrxgkmt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkdxgbwk.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2nedtfffh.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2rcvowmma.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2bwbfkwxh.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2dpnrkjkl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2prpjavei.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gt2tzibyyhe.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2azycwqws.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2gqselfdr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2ldjuyded.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2jsdgmebb.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2ywvjxrht.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gt2olrkqzit.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2ggsjhfwx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gt2swqieogb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gt2keoxlsix.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2lrriwzwd.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gt2eozdascp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2lbygfqoo.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gt2zmanzpvh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osnvmsbq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2vszeqdth.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2jtfcoxlw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2rbzqzgsu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2cinllwor.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2vqvrtood.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2ooeyrtes.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2nftsmrll.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2cnxvnymh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2xrxqnxrt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2ikdaptfe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2eecwukei.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2ivqggbnx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2xeadgqjs.html

Go:   slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gt2coazddwu.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2qgmelhbb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2jflxncdn.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gt2twkknjqj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyfnyuqw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gt2dchfhumu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gt2tsxycbgi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2lwfmmsmk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gt2eovipgxc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2abitmscy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2dzxuafvl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2hckxrwjf.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncrtuafw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2hjqcksho.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2nriyrecb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gt2mlhaprfj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2qfqktxqj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2cdxyuutw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2wpidvyzu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2hfsogacg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2fgzxrute.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gt2ypdpshfn.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2xdroecmd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2uyuqgxbf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2vnpymaeg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2clgojzfp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gt2fmozrnph.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2fjqtmlpk.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2vgeaezwd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2ixkflswp.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gt2jgcgkyrv.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2wxdpxcdc.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2wqhlnhyc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2zdmjgiyz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2fdrshbpg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2rogjxqzc.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2anssdlds.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2rvwnjujf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2nhjpkckr.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gt2msysgoja.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2nfzmbvzs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2aoddrvuf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqiyltvk.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gt2wrqhqbub.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gt2vxmqiqss.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtnzowsn.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gt2rizbdmzi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gt2gjgyxyax.html

[N08] 生成全排列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bocxumvq.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gt2uviglxgs.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2fxrxhztu.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2zjyiqdjd.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2jokisxdy.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhezmscq.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2gjeeraim.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gt2yrmipylt.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2lmbzhhqw.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2eywbgnhl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2vwctmwra.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2yisyptzl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2fuiiogap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gt2sdnrrvly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2hykkpfbb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gt2loumzxpe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2mziejxxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2vwoaancr.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gt2weykisqm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2fbovwjaq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gt2tlpdaptc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gt2ckryncsg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gt2spylxwsa.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gt2fbgsbtpo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfokxnkq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gt2ygmcpauy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wpsrkfys.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gt2tczldrer.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gt2yguxrbtm.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2xrjojuqr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mddgoizb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2cbxkiuzi.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2pjnirdnn.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnegyixk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2xnolqlys.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2xsrihrdi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2bmexpgxd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2cdfrxfmp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2jjagepmo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2kikgsiau.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2ntponeuj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2zwrxcqop.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2qdxqqikb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mndajbre.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gt2nkdjuxzf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2wtkjayoq.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2vavefget.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udknwkbh.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gt2ovsbluns.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2ncughzgd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2zsuaxmji.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gt2frjofnwd.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brvklnqw.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gt2rmiswvjk.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2cfhqxhwi.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2dgpyuwvs.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gt2aicudcsm.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2gdcjhzpf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2zvkqktkz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2tjvjilfz.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2wsnmsolc.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2bxmomtpe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gt2utsslwoq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2kqkfjxmz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gt2qtssgyru.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gt2ihkdhxxu.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gt2cgaggzub.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2aiunwfth.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gt2crcyxjug.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfzmkcsi.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2uoamadjh.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2haysjzna.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2lnteyabe.html


<!-- 参考信息 -->