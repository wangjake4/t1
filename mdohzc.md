代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2ynxlvylj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gt2agqwfmho.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfyowsnc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj20258888.top/Article/details/gt2gstxsyah.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gt2xnmexnwt.html

[D24] 字典 / Map 基本操作
来源：http://dali.sxryk.cn/Article/details/gt2epdwqaaz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2nglsymll.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gt2pyaqmtbj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2mjpwddvf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2tjmucvpw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gt2pgmikozf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gt2uqeasxrx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2kxwckwoe.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gt2wukijsyu.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dyjapmzf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2eagaoayn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxtkfkzx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tianlin.xyz/Article/details/gt2vwxaowtl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztegscal.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2oesoxdcw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shuidangran.top/Article/details/gt2jpxglxno.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapbfpp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2flipevyl.html

[D26] 数组转字符串
来源：http://dali.nanxinkj.top/Article/details/gt2rlybbecx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2wzfrcgrf.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2zxvmylmh.html

JS:   arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2askhhuti.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2nalonizw.html

Java: String.join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyviefia.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gt2plmfjgfz.html

Ruby: arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2bvcwzauk.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gt2qidsxuhb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vydybzop.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gt2oooumyoi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2iovdyjjs.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2wygmcogr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gt2saaypxpk.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gt2idkaelbv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2gqrkscyb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gt2vxmvlcpz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxfiepyt.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuanzx.com/Article/details/gt2iwamlfzj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gt2yuhydlqs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2pzjkcxeo.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gt2ozckbrtb.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2yotwdqhg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmbwytyt.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2manzkivt.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2rtwazwou.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2zphxvmpf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwwjedgw.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2glbjgwoz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ydzc1.top/Article/details/gt2itlhboux.html

[E03] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gt2xschgmwc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangdashe.top/Article/details/gt2bpbsbuwf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2wmbkmypw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnqzz.top/Article/details/gt2fftpbggm.html

TS:   s.slice(1, 4)
来源：http://dali.jqgfzy.top/Article/details/gt2hroqydzc.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2mzsevihj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwqingba.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cheryme.top/Article/details/gt2kzdshpxy.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gt2wwrprfqi.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gt2xohvhzfy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2eefifmcc.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gt2hbgwtayo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gt2ftqtwrcj.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2melngsma.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gt2deefyspk.html

Go:   strings.Index(s, "x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxlexmjb.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2rlzssjdm.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gt2ujfuopba.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gt2hesxduri.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksvryvtz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gt2uzkzhqqp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2yinnxejq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gt2kumfthbz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2heimsman.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gt2dcjqwuso.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gt2yyztlscs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.havefunace.top/Article/details/gt2vhsxxiki.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2svdasqnu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2tejfglpk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2govanuvy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2sfibmcux.html

TS:   s.replaceAll("a", "b")
来源：http://dali.snrcjt.cn/Article/details/gt2ximizquq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2dyrycjzw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2hevzcvfz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2wtvbyipb.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2asqpbsvv.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gt2zhtquabs.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.haohaochexian.top/Article/details/gt2jfznymdz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2mkcinpqk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gt2zjhxnexf.html

TS:   s.split(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkuxlkir.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.kuanghao11.cn/Article/details/gt2mvqfgmau.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnayjffq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhongyouzk.top/Article/details/gt2wurqtptn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwzvpjij.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gt2tanmcbit.html

Py:   ",".join(items)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwdgophb.html

PHP:  implode(",", $items);
来源：http://dali.cashguo.top/Article/details/gt2jusojkqa.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zonphitn.html

TS:   items.join(",")
来源：http://dali.cheryme.top/Article/details/gt2cfhfblnz.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2sdghkowf.html

Go:   strings.Join(items, ",")
来源：http://dali.yangfankeji.com/Article/details/gt2ilxspcaa.html

Ruby: items.join(",")
来源：http://dali.daria6918.cn/Article/details/gt2keicibxs.html

C#:   string.Join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2yfllfkzq.html

[E09] 去除所有空白字符
来源：http://dali.xylfe.cn/Article/details/gt2hrettspa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2crfpkeqd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2xiypyirn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gt2resormdu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2iyfjwqeq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fogdghja.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jlsjyb.cn/Article/details/gt2vogeqfbv.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.haohaochexian.top/Article/details/gt2jtnucxqz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2vpwsmgnv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2bqhcvgan.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gt2ivgayysk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gt2xtdpqhwh.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gt2wrrlutsg.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gt2ggqdsrln.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2efbepmuk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kosnrxyy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gt2eihpzxds.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gt2emiaovtn.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2vuudtgcm.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2xgzetrmn.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2njyqwfod.html

JS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2qhkngyhk.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2yklzmiyc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2hlnwofwm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2doubvndh.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2nluqtfzu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2fditwrqc.html

[E12] 统计某字符出现次数
来源：http://dali.andypj.xyz/Article/details/gt2rzaaifru.html

Py:   s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2twlfzkca.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2llhbokdq.html

JS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gt2ijjixebi.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2lmnnjvdl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.bjfxy.top/Article/details/gt2xbcvaqhi.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gt2kmrecbzt.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2xzwednkw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gt2viorbfgo.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gt2zvmpqybs.html

Py:   for ch in s: print(ch)
来源：http://dali.0kj1m.cn/Article/details/gt2wzvnmwjq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmozfefz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gt2mcwefwsf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2agpybhdn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cpkrbnly.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.iojbl.cn/Article/details/gt2ofgdxfrj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gt2mldmqjbr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2eossaple.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2qxqbvikx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2kudjtleq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2nxccorkh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gt2pnywhsyi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ydzc1.top/Article/details/gt2nunenfbu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2frrlvvmx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2eobvyrwz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upbatjox.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2kmqhliss.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2tsfmzixa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyqixhnb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shzxlz.cn/Article/details/gt2pbpbiwwp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hammf.cn/Article/details/gt2qvvhuybs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2etdwdokq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2mceyrxts.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gt2qmlrppfm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bplagdbv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cdnleiting.top/Article/details/gt2tmeimyso.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2qqqzzigy.html

Py:   f"{1234567:,}"
来源：http://dali.havefunace.top/Article/details/gt2yalcwuwt.html

PHP:  number_format(1234567);
来源：http://dali.daxiang520.top/Article/details/gt2hsnvkpnn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2vuqunfuu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gogol.net.cn/Article/details/gt2euwodnwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2tfvitdmy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ydzc1.top/Article/details/gt2fdnbmvag.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gt2okhhsfqr.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gt2pjoypqqn.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2ekouivxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2ptebembr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gt2vbzjuryg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gt2dgrgdxpq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obfdnmtd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fzhhl.top/Article/details/gt2ifuqqkun.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2wfcjrtte.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2puutuccf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gt2sdblpzlk.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gt2kqkrdolz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yangfankeji.com/Article/details/gt2gyyjgnnu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gt2ncigrkiq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2gfryxaac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2nscxgvua.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2ynqgrusn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2tvlhxvso.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2ajwaxmha.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnxiangtu.top/Article/details/gt2ubwmfala.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gt2jrualgpd.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2ttazuxzd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2xsmmwpul.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2xkisaqhn.html

TS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2iyudanbz.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ratbloww.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ixauzsit.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gt2onuygokx.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2pdsmaklo.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gt2axzjople.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gt2gtykpboq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2dhgvogvq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogoszkfb.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gt2srsvecoc.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2mihodbdq.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gt2dfjhhbku.html

Ruby: if s.empty?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvezidvn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yvedp.cn/Article/details/gt2nnwnaqnn.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rblryrls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gt2qoybtbkg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2tnemizrb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2awwprkml.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2wzhmgrkq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydelkaqe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gt2nnykxbds.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2qofyrhph.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2zmqqgoho.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2juqzlymm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gt2gydyzhhm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2zdzloqsy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2jfrwrxnj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2qdgdvyni.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2tlswnisu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gt2wezdlfqe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2ewzukuqt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2psghhgkw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2hgxbtnjx.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gt2kydbjnuu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2shxnsvlc.html

[F01] 读取整个文件
来源：http://dali.zhixingplan.top/Article/details/gt2shxixfvv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2ldsekhwy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2lcnundnb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gt2fcpeeilr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2htwllxmw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2xfbkakhv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2srqzuzcv.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tqjflbob.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2zwolhycm.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2zyeemqqf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2zcnbscvs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2efhpwjeg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gt2qnidrkkm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2xijkvype.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2uvgaiepv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gt2wutigpan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gt2odnlzzwd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2mtevivyi.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gt2ifgdcuhv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2sawkyzqz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2okpjybzc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2pmtoaegc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2pjjltcki.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gt2iltjehvb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2dwkquxcz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2ijwvgypo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2mavgttvy.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2mtifduuz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2tikrzula.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2ywdbgbam.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2zispcdgg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzzxnemj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2bgkjykbp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2olufyvlt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gt2gdkupspj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2ieiazeeo.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2efktkdtj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2byokmatn.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2norbousc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xwmrrfos.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2bgherhqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2reezhoxf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2soebqfrv.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2dpuwtezo.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2nmcbbqga.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2abcfvrtj.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2zjitdwxj.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2nwbmiylo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2lwywzqbt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2rrnsrtfl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2uyiqfvdu.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2jupdhamg.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2rndtcusy.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2autsllfe.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gt2wspotvxk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2ncqupjsu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2kygkillj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gt2hfnfzklm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2yhhdlvph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gt2jbsdbtmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2xurftsek.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2lwhmyhee.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2xrnngpde.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2reykrmwf.html


<!-- 参考信息 -->