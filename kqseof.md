代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfinotuvh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnwcpnrr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtfoflepst.html

Py:   pickle.dumps(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpvinbzcx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtpsqtempt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gthxkhfjlo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtovydflan.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gtrxtbpqjd.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtdmguoecx.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtclptjhoo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtyohlpxub.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgjayluna.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtdaaowgpw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzzndwjac.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtlqdhnjhi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtekhxihvl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gtkzmllcvu.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtorugfhcu.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtdpnhumth.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtjquxtxfx.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtpdaypmkd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtglpzkogu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttozcwsbb.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtvyeurshf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gtafpdvfmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtphxjhoad.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gthukyuhnq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtyyjdoyds.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtmlifqoue.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gtukdpuhsd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtfcyqdpvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtriaxmznm.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttouvytlg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunsdynbr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtfjykuwwp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gteivdmuyr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gttsmsqhej.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtfqyegxbd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtzmgcpvtk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtvuazyntj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtrrsiszso.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gtqtygcsuf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtnqtrylze.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtihggweiw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtemmpbcpn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtitvsqzyi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtdzandqeo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xziqi.cn/Article/details/gtnhowdsfe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gtqfhloxvn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtymftfcvn.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgbqojse.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuhzgphh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtinnlflvu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtdewlqpyg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtujwqwsra.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gteeimqvho.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.andypj.xyz/Article/details/gtbvgddlto.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtsspqzhwx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gthszwxfnv.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtlhhcjnns.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtntjshwtb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtybtyqtjt.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtjiplnvol.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtlrohquco.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtlrakgkpw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gttnxwbrrc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtgjpqbvpl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtoqgenjay.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gteqbbhqgz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtskfhfobf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtvtgtlrpl.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtumlxmoqq.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtdbimntrd.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gttwxljeha.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtcjhdzymy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtqbeuproa.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gthpuhgvuo.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtctucmjff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtbizeyvif.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtitswztym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqfgqzppz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtpvfyawoo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258.top/Article/details/gtftedmxpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtolycbfpi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwpwnmlv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyblrourn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkzcamzqa.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtlknjdwic.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfbvahcbn.html

[M01] 读取命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtlfmddypv.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtladjaxud.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtkvahtiej.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtrvpvcfsp.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtzqgmyvdr.html

Java: args 数组（main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtzhqqqxlg.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtrtnxhmml.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtmmjsekis.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtokukjaln.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtinblvwsi.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gtjyuyudlv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtumypzbhx.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqwcngow.html

TS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtmsbvzxfa.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtlntpvqbs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtlknjxotp.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gthtopmgxv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtwgpqibxv.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtlxjryoyz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtluxdzmui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtpigavqlt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtnrxzowmt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtzrvxfsuj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtrffprjwz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwcudhjm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtwtgknwlk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtktukomdo.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gtomixbsxd.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtvgqzlpvf.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtjqxbsonq.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtwuqujsaz.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtkjlhgtcr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtsfiphlfi.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtrolcdfkb.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtnjciazmb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtsqzxlpdz.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtypygxzdl.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtiamaxrdv.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtzvqqbelh.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtwvpnfqqo.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtmeaikisf.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtkowxsrcj.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtagqryhzs.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtsshozqin.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gtvtkfpdfs.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gtzoqtopte.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gthwbopiqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtkkfakdeb.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtonugruze.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtycdnjevz.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gthuibcyay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gtnawljizg.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtacfmbrlg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtkporlxzp.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gttdlwhrkz.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtqvuevwap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtqoengqhp.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtawbyhzsq.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtwciwhgrp.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtdenytcxw.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtyfdgmsdp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gttgcsygny.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtnljczcrx.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtmqiotplo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtvkqqqsnp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtfsuwmbea.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtyzpnihhh.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtrgbtpibj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtbelhfwrd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtipjyujgg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtzgcubuov.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtgplinrbb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrrdplhxx.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtjsqsxepg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuwaofqid.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtpawdrbau.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtgicdfkiz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtvdqtdaoq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtvfnqcmgd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtclxkjvju.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtaptdghoi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtbipkpbfk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtlyxkylsc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtnigetthh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gtkhkoldxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtmxvradto.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtvcarheth.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtiakmegib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtepwvpdza.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtpefeiqow.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpaemiqo.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtniefdnoo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtzkhjiapw.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtmafntkse.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtbtbunpgf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtrqkykfte.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtmwmkefit.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtlxjavoqq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtvycufbju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtrsohzlme.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ehwqpu.com/Article/details/gtwjjyertc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtvpzifcmz.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdejynwsq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtuehsvedx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtozoqhciy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtrwmzltff.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtyivfdryx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtffvjmtrf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtmhfmgyos.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtqjjqypfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtynmorhnr.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtmqraelyr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtiqojqhlf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gtukbuebwd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtpeczxiqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtnobovmjv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtmuvavngb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gotoacloud.top/Article/details/gtqgmktlzc.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gtntnbifif.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtdjzonpnm.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtwgaziryb.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtjqcnrftq.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobdoeeqt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gttiomrdit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtqpimuyvo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtyfnnbjyj.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtenpcvare.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtzqfctrfe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gttewpzbum.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtjhrelxfs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtdmiaxvoz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtuujxtlkj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtbulddulw.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtljmpdobq.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtxrhfsoxp.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gtbrtinkaf.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtsizwjbyp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ydzc1.top/Article/details/gtnoutpevb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwmudimi.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gtblyrwvss.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhvjxvlv.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtqerubdtf.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtqkhqyrwc.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtmrnsreji.html

Go:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtdddgmaba.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtgxtglmns.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gttsnyvdcf.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtozrtgbdn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtpulwtprd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtmshptbes.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtnzzaycdg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gtwmuinglh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtsgvnpkxm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtzrbjtobx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtjikjymsf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtuepcthrc.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtuzfjdlmh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtjzwzklpw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gtegzwqarn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtmmsgjcqr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gthfloezcf.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtbjvxruca.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtinwmirde.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtsvrqaqna.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtmuouujuv.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtgvoyyqri.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtovfpbuuh.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtfmnphyga.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtchnqqjbc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtdrntqvdp.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtldmhecuh.html

Go:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtodjghlnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtzhimuvot.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtnimgkebe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gthvqvkjmh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtspgzxqzb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtleeuvmaz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtekbkfjkm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtcmkyibcl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtoywbqvus.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtkkvqsfdg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtpyyclpfi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gthljsrbho.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuhvjbrtk.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gtaaqgjqql.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdcekfhvt.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvwkzewv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtumnedspn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtihczphzh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtafmdasxz.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gticaewsgm.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gttcpnkzzq.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtkymcajig.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gttdhxmjjy.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtwmxbahyx.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtrpwloceq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtijjqvuen.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gtwymtbaym.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtdyrccipk.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gttzadvhfu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gtlwkzlebe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtapkbciee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtevquccwd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtykfidaar.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtgodmemrf.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtwevbbrfn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtwteygbsp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtcobvpprt.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtcqmnvngq.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtfgubvtlw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtaiwiqhvy.html


<!-- 参考信息 -->