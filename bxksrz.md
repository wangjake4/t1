代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtmhlwmfdv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtrdiobizp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gthstszxfi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtxvbmfccn.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtlxewupsx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtdtwjbhif.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.0kj1m.cn/Article/details/gtzegpebaw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtiizchwcw.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtbavmfxbj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthpafhwgs.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gtijwjioxg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gttblyymiy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtslccebyz.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtuintkuis.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtzgjpbljc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ivvv.top/Article/details/gtykrmgauw.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gttwnvoywe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gtirnwkvuu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtcpxsnfun.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtersxgfvn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtoauoqlkt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gthgvaglky.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtuinotbfh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtwwnjrtuw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtjjgccudg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzekqeggy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtdfhxhdwi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtiqcvljkb.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gttgtdovbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtqolvfsve.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtkchfuejr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtxiebflzj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gtgyllzkef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtyoqgqcxv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtkrpaduly.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gtakxaqmfq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtfwnejfup.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtcopjpjad.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtrfewjvhw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtndfatlog.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gthnmttygh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gttvqxjfkq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtqiomzrjs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtleakdeim.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gtuqqjhjuy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtdcoaqdzq.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtcwthiobh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gthkpiukqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtohcmklbg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gteqrsxknk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtpgfqyywr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtfpawbyqe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtllozrslc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtxgckjudb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtjynvywol.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtftvouhra.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtgethgtgh.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gtuyaljmxs.html

JS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtjyppoxqv.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtswvtbgmz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtusyadohr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtsjccfwxz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtwfirjlmt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtlehfbqhp.html

[L07] 处理 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtxkbsswrv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtxqpinceu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gtrzfojfkw.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtyorlrxes.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdbxughb.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqzxhtav.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtovnafaon.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtemerwsae.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gttcrqdxap.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtpamarsql.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gthilssfuw.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtqvseemtd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtvsjbfxed.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdpogmxn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ivvv.top/Article/details/gtnuygecsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gthqqlnbfn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtdfnzaeev.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtrzlndkes.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtreqttsfa.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gtnuuvluif.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmuaqsbwk.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtzcljhgew.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtgpqccgtb.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gttzvlapjj.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gtunmpvgfh.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtcgippbsy.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtcrjpilez.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gthjcfthmv.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtnuqpawkq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtirgaihmk.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtnolccvgn.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtjqzxlpbq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtmpqycdri.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtwsrvcmhl.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtabxlotgm.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtozuwimif.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtwgclwlnl.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtluratzwo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtlflilktv.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gteiaxapcp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gttrtewfzf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yuxming.cn/Article/details/gtspkpdiws.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtuifddtzr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtdkciolxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.redwolf501.top/Article/details/gtjbkvdash.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtqphhxjns.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtvfnqadtl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtmlhmjnui.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtxdzcqicc.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtvcxzyxuf.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtgdnqwqyr.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtdulbkzgx.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtquueriul.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tian-w.cn/Article/details/gtaezixred.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtvszlbgks.html

Ruby: Dir.pwd
来源：http://dali.aizwys.cn/Article/details/gtiwuimjqf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtcgthfgsn.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtbeflnsac.html

Py:   sys.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtczvrpdct.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtmrkvczyt.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtzugkixmi.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtcgsckejh.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtdwbrxgud.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gticrljbnq.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtsgtsutad.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtlctxjweg.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtqwaxkwdo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtmwqwivfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtfljxklfn.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtjekwcohf.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtsqijpfsf.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtpjnrdxvm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtcapygrpk.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtkozdzize.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gtyhevjdiz.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gtfzxgwszf.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtszwvdter.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gteqtbglsk.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkihhrao.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtxshmeimg.html

Java: public static void main(String[] args)
来源：http://dali.cdnleiting.top/Article/details/gtlbaubage.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtbccpndna.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtjkodezjh.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gtvinqutij.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtiibogrri.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtmdooervt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gtvqcfulym.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhyvynlo.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtysxqjryt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtvcxbgegq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhvywwos.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffoyaqws.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtxmmdlxei.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlykzuivs.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gtgdjyasoz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvkvzqpqj.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtwrapkcun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtktycpmrs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtqlfviobr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gthhriwjfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtxyrfuats.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtrdinxezm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtstoealnn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gthlogyrsy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtoxznpaoo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gtuzclkibt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtaqzaysfx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwsntysd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gthdzyyhre.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gtxpcjkwru.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtlxobjrjd.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtgxsbzssm.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtbpqdocoe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gtffsuetix.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtkpycnkjp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtebfbzqme.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtndypveaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtqdpmnrvg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtgsfartyd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtizunxprc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtovaabmpb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtzzgbzses.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtzxmiyfre.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayxbsbou.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtnwqbkcjg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtfkrxover.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtslovozgi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtjlmkbuzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gthkaardul.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtjbltnpmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzwrcpjj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtwdyhtqvh.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtmyinuseu.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtujhmtpbt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtbxxgxfoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtkdtmykqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtqcwzmoah.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtahjaicta.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtzigywflg.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtdybxyain.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gthhlugmpa.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gtszaqugqo.html

Py:   s == s[::-1]
来源：http://dali.ybcxt.top/Article/details/gtulcaxcfr.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtvtwhprgj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtbayxmnce.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtjtxrbapx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtwizmqnag.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtgnvbkxca.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtwvgwyjll.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtvjcgatti.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtrbcqvqwh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtrgddbnku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtrxvmwwio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gtdugzqqgr.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtdcdfqqbc.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtqddjlbht.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtpgahbioz.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gttusqqbzq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtircuusdo.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gteuangyvr.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtcqgvnezd.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gtltjzdfty.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtaumblald.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzsnopag.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtdzrzfyqy.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtyamwjgqn.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtjzptphhh.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtifbxvltx.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtijevveyx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fengsongda.top/Article/details/gtaacwxgjn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtaiqirqbk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gthslkivxz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtofqoisqs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtmzjdvkei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtprhraith.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdecdzzk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtooizqhfd.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtdwvtltan.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtfukpania.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjddzpmd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtjlutbmec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gtgijuzryl.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtjegfyhmu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtzqlbgczt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtksjfrzso.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtmjksweok.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtvrniinof.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtcunzarki.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtsjkzuyxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtgdcbnqud.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtqupkekcm.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtdfzcoopa.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gthhmagwxq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gthnksvimt.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtitdbewvh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtxmtcnzss.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtxfsaavws.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtkiwetebu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gturknzrhv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtszeyikwh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtvsxswptz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtidpifwka.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtjczvxmkk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtfagggoed.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlduoxfnr.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtmlnduryn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvuaxbumj.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtcilrjblf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtkpgfvvex.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtsoriamwc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtcnbhhybb.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtdujhbegd.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gtzjokdtfs.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gtoweqwlds.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtugpwxwrj.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtcccdmijp.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gthmsugjjr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtxayhrwyu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtojvvwjgd.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gthfxnglcw.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtwtrbwptv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznsaeygt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gttyhydhcy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtilmzegjh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxtijfhm.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtnonwrdhy.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtdxhvqipp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtrlwkgzib.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtanjohmks.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtiaarszdi.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtgvymkwyj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtdkorcvhx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtkfobwkmg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtlnktxogv.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtnftceknb.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gtarrzdmqx.html


<!-- 参考信息 -->