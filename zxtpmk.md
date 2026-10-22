代发 wailian999

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2mysvcyun.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2plpumfnh.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2olwqsjuw.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2lhrypzaz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2iotsruaz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhixingplan.top/Article/details/gt2fcgzhglp.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gt2udomknvf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gt2nujfeqzz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gzhubu.top/Article/details/gt2bagyqlve.html

[D24] 字典 / Map 基本操作
来源：http://dali.9152youxi.cn/Article/details/gt2stjcggtp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gt2iziycsog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.nanxinkj.top/Article/details/gt2leehvojg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbjivinf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2mjibwmsu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shzxlz.cn/Article/details/gt2pmxlnwla.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.fengsongda.top/Article/details/gt2lsnukwhy.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gt2rsezdfpz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2hgeswegm.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2cylbgjif.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gt2sjbzojnm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gt2ebyxandj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gt2gzxcrhit.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2peiqpunv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gt2prlwnavk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gt2rbulcroi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2vlhrpagi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2kedyxltg.html

[D26] 数组转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2jyyehyiy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.guannengcc.top/Article/details/gt2anpikrjd.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gt2awmdvafu.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2izseqysp.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gt2pvdcrdiq.html

Java: String.join(", ", list)
来源：http://dali.jqgufenzy.top/Article/details/gt2mpcgwsnn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2rmseldzr.html

Ruby: arr.join(", ")
来源：http://dali.quarkkingdee.top/Article/details/gt2ufpshtgi.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gt2ngoicgof.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2pcbtnybf.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gt2cgamqcri.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2retibqgs.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2hlvtapsn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ciemxhpy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.quarkkingdee.top/Article/details/gt2wykvawgy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2odzrltss.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gt2tobaoerx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2zkzpcpdd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2xmwmgrjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gt2uanxwzfs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ibhobiek.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2amrlodxk.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2ochmmfdn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cheryme.top/Article/details/gt2nxsqrwqr.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnqtewax.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2ldxqpyah.html

Java: "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gt2kddfyuzl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gt2dajyaaiy.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2lkedxsxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmhlhrhg.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2weoxqavc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gt2fppqlczw.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2fgnjqaiv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2gjxqkliu.html

TS:   s.slice(1, 4)
来源：http://dali.ydzc1.top/Article/details/gt2mdbhtmud.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2snlyrpfe.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2fiigjrsx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2vtvarpss.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2mevzvdpx.html

[E04] 查找子串位置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlqucdon.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gt2zyxlivdd.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gt2unduvneu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gt2dliiweqy.html

TS:   s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gt2ztcgiich.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2gkzezfcq.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gt2xpgdlpyg.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gt2dgsubexp.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2gowexmrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sysykeji.top/Article/details/gt2iprfvmds.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2vegrxnlz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gt2teftycro.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2fpzegmro.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2vndcwifu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2qjcoifai.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gt2asveeupc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2mtxgobph.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2tpchctku.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bmrnhdhn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2viaxajxa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2awbyjkmo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gt2ygexoliq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjbangeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gt2jsxurahk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ijzkkbay.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqcxumjt.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2zbxxinuv.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2psvnxiue.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gt2mlaecxcp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2cqhktwpy.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gt2swzzpjtf.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2wuiqpcmt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cqqwz.cn/Article/details/gt2zbgbbggu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gt2zdkwmkdt.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gt2mwqkayvl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gt2tocfjpvk.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gt2mpcfkiaq.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gt2qbbfowxg.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2lqvgnnpn.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gt2paoyydpb.html

TS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2edlpckzj.html

Java: String.join(",", items)
来源：http://dali.pycfn.com/Article/details/gt2ljnrosqt.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aisdclmj.html

Ruby: items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2icoaufcj.html

C#:   string.Join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gt2qxtmhayh.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtkugxcr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gt2dabxjjrp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2eepeahxm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2chprsbcq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gt2fczmzmwn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gt2zblchkjw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2byozdsma.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.svipenyu.cn/Article/details/gt2paogxxzz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gt2gomehqjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tianlin.xyz/Article/details/gt2tmdwqmkg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2cgmavdqa.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zycfv.cn/Article/details/gt2dvwvfsyz.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2qczxwofu.html

TS:   "7".padStart(3, "0")
来源：http://dali.havefunace.top/Article/details/gt2czoepljs.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gt2yvffuljh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywyugnja.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2wiokuqwc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2mdaxqkpy.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2sliyihhn.html

Py:   s[::-1]
来源：http://dali.316326.xyz/Article/details/gt2thjbsgan.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2gctwdfcy.html

JS:   [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2okloyqvw.html

TS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2shflbsup.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2tixhyuek.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2gypsbstr.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2xdxxnbsx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gt2bjwahyjj.html

[E12] 统计某字符出现次数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssfpcefn.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2tvbkhniw.html

PHP:  substr_count($s, "a");
来源：http://dali.c1oappe.top/Article/details/gt2udlgzgih.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2xlvuskoc.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhrneuwe.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.snrcjt.cn/Article/details/gt2bkuvgkqt.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2sbcyjwot.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2hhevxiaw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gt2zryclrwk.html

[E13] 逐字符遍历
来源：http://dali.yongpay.top/Article/details/gt2prgbvwcc.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gt2eklkwgxq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2ltbwtqjk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gt2yhsjxxml.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gt2omdxxrum.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtpomsqm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ohopcjqk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2zeoyavqs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2ssgnusvf.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gt2vmcwhnml.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gt2dmhafvkq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2qqgllrjk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2xrmxxzwm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.mhx1999.top/Article/details/gt2zxqslkfr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2ofpuzllt.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shuidangran.top/Article/details/gt2bjjuzggc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pycfn.com/Article/details/gt2ybcvpxai.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2xtgsyxcd.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dciwjpne.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2vbkeahty.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yongpay.top/Article/details/gt2kqmxwyve.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinqigufen.top/Article/details/gt2awegoldj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aizwys.cn/Article/details/gt2djselqmm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gt2bpgitwio.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2gbzungcv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mlxonfbw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigufen.top/Article/details/gt2kvpsezmx.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2ganpoiql.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gt2mlzzswdj.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gt2kpglqygf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gt2dqmfzxpg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2axmxtytb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2phivxrlp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gt2hagsbisj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gt2wokqswsq.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gt2luxgzfpg.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2opkwmbfn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gt2jdzyjzsb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gt2fowqalbq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2idiybajx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2eejzhvvd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gt2mhuuugve.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2xfnkypdl.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2letwacbf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gt2btydjeol.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2vmvumzul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gt2rxuoiwya.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2ffmchxfs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kowhhmsu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2qfsnfzrq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2wwerpglb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2xtjmifrg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gt2buagmrdm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ppjwa.cn/Article/details/gt2wjrumicw.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2ofxincuq.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gt2yigahoxh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2xebwwwre.html

JS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gt2grantdio.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2aujpiubd.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2cvdjwfkf.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2ihdrpgln.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2efdmzghn.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gt2wvarevjp.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gt2kopylyta.html

Py:   if not s:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loaaernl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzcyvtyc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2xvfktnhl.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2blnlhubp.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2dncihoij.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2bjzpslvt.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2zsglwiik.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2hgdofkax.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gt2jreigsug.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gt2nxsldtki.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2hzbwupbm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2yiknhwsg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhhxhtiw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2rlmeqihp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gt2vhxffwjh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2qjghugaq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2rhjqvbif.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gt2gdkezlaq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vzxqtdfu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2ixmlixze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2pwgwbntg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2tmblsklb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2abcadocy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gt2ruyllops.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2qwphuqsj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2dxbxqege.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vihwkoug.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2tibgrcrg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hjjfxnkm.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2ajbyenzg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gt2krrpwcru.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2rgwwcigy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzfiqhqg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2cjvsemlk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2ivlttwpj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyeqdfk.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2kumimdjj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2vgzjwnqv.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gubxhpgv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gt2aybhcyhb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gt2cjlazgdg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.snrcjt.cn/Article/details/gt2werzmvyx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjtcawmq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwcggsjg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aihavcqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gt2nqeoqecj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2pihsrpbl.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvdhiwwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2rlngwtzs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gt2zdokescq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2dbmcrnmn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2jmwvmqxm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2rishhrhw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gt2rcuvbywk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2unnspffd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2ceslijym.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2tuanwayj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2zvvighht.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fengsongda.top/Article/details/gt2uacuridu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2xsndhtpi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2kvwservr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2wghqhhjd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ulmmlxhp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pycfn.com/Article/details/gt2tuvalwfr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2zchbtaju.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2wkjdwyld.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2wugvgihm.html

PHP:  file_exists("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwpksstt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2gkefbemb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fggmmcyr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2ayqembqx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gt2tfuaoyxk.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2eyulxqww.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2fpsapozi.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gt2wucsscjp.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2taseshju.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2gmjazqhw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2esxcxmlm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgmcpana.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2yobyvynw.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2phqggwpv.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2schapdkp.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2crupmfgv.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gt2woaobedk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2zrnoyzoa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gt2vkgdppio.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2uirbxups.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2butnjmbm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouvpoowe.html


<!-- 参考信息 -->