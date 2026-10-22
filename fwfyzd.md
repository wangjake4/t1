代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhllofum.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxinkj.top/Article/details/gtccnmifbm.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrshktbvm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.c1oappe.top/Article/details/gthzqgcmgt.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtwpyjlvwe.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtrrogpuyv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtdrjetmgr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtrwtzkasc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtpholcusb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtodzrjmev.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtuvtmcvsy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yongpay.top/Article/details/gtaxhznwoa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtlqkfrdbq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtoesxamva.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtyjfkgehj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdogaimsb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtfgiufqem.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nanxuanxn.top/Article/details/gtafjybpqx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gtkijeazwn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtschxqdmu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtlczyelhq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkfzoxpyz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nwbrower.top/Article/details/gtbdznbawa.html

[D26] 数组转字符串
来源：http://dali.chenlongwang.top/Article/details/gtenqfdacw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtrkwhvipx.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtgnviseld.html

JS:   arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gttcuzqiuu.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtqogbfono.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtkmoyeabf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.0kj1m.cn/Article/details/gtukiscwen.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gthcohkbgh.html

C#:   string.Join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtonchaqvj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyfqqoikr.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtlgktsxcq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlaubfygz.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtixodrbng.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtahgmtiej.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gttnnkwsyk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtxpakmoes.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmillozwu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.9152youxi.cn/Article/details/gtoxlrfkpq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtezxqcncv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtctbxyziv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtvbtndqvw.html

[E02] 重复字符串
来源：http://dali.aibaodan.cn/Article/details/gtcxyrxibx.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtqghbjodf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gthqvqykev.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaisboqun.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtblumlspx.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtbdkuryrk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtxlcmpgmo.html

Ruby: "ab" * 3
来源：http://dali.cucudq.cn/Article/details/gtwfxwaots.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigufen.top/Article/details/gtyfuxopeh.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtmctvlwhm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gtkhcijgoz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtpmzekjmz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtesqwdpyf.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtsohrpiti.html

Java: s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gtxndizopf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xuanzx.com/Article/details/gtxunjunob.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gtudjaalxd.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gttkfgkmaq.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtgvzstjhp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtsqycwacc.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtpvkcmjqn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.haohaochexian.top/Article/details/gtaiexjezi.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gttsydhihp.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gtypdhgqsf.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtdszdtcja.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtlbgslsnp.html

C#:   s.IndexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtpklinini.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gtydpeozjc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gteygiwfaa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtnzihkfoa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtyjwhghjz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gtqptlhxvh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gtkcpjuuse.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtogrzjpre.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gtvvpeapfl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtagkebyfd.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtbisngzka.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtvjoyyqqh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gtlstymtod.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtzinrdpom.html

TS:   s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtflbjjdbh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlppmlozd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtiifylonb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gttolegloo.html

C#:   s.Replace("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtmvaanaib.html

[E07] 按分隔符拆分
来源：http://dali.xinyue.icu/Article/details/gtbuqnoetr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtuamocqtf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtbbothauc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gtkqdaaksk.html

TS:   s.split(",")
来源：http://dali.daxiang520.top/Article/details/gtqcelxdhi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yangfankeji.com/Article/details/gtsugvcdxz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaudfhpdz.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtciiunwgw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cucudq.cn/Article/details/gtxzjniqbz.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtpbuweywp.html

Py:   ",".join(items)
来源：http://dali.shzxlz.cn/Article/details/gtvzzvtusy.html

PHP:  implode(",", $items);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyimkgiu.html

JS:   items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gttmicrrbr.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtbmuivlic.html

Java: String.join(",", items)
来源：http://dali.cqqwz.cn/Article/details/gtqurshpvl.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtzzehopen.html

Ruby: items.join(",")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvukcxlpg.html

C#:   string.Join(",", items)
来源：http://dali.yongpay.top/Article/details/gtdbirbbtz.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangtech.top/Article/details/gthfxasflz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtnlwwbnqu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.andypj.xyz/Article/details/gtvtgjbgmu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gtfimajbcd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gtodzitfew.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhiwuduotai.top/Article/details/gtlahnengp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtsvqclqoh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtmjvnnkyq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gtjuhtprwa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtubuesppz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gtojuedzez.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gtkqahgcav.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtoofnaavf.html

TS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtpqucniih.html

Java: String.format("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtzqskspng.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtwgzvtxys.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gteeabeprp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhiwuduotai.top/Article/details/gttckpgpsa.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpokqaqq.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtmujndzzv.html

PHP:  strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtnarvnkbf.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gthwxhbxkr.html

TS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gttbchnedj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gtlpdyqsgj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtnmlmgumh.html

Ruby: s.reverse
来源：http://dali.hammf.cn/Article/details/gtdhoboiqe.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtqnslnjoa.html

[E12] 统计某字符出现次数
来源：http://dali.zhengqikj.top/Article/details/gtycnwuyor.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtkkfxvvzc.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtsingfcru.html

JS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gttfgumkqe.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gtxctwlxag.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtigybyxcw.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtibmnxnvg.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gttikywhxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gtwkobnsgs.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtnguzadbz.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtxhucxgvs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dianchejie.cn/Article/details/gtknkttqov.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtuotdburc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgifwdkcf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtibvjycwx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtzsfkfzyk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gtxiqnthvw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.wangdashe.top/Article/details/gtvjpcdjbu.html

[E14] URL 编码与 Base64
来源：http://dali.feifeiyinyue.top/Article/details/gtwidzpndy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gtmpfoekgo.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtktackybi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gtkcjvsofg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtlremidhp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtgkwhfetq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xinyue.icu/Article/details/gtjbsseond.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtoojdjhnx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gtvunsnnsr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gtaurxcfnm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtqcnvvdqz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gteaexwtfu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gtkklwwotk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.smart0.xyz/Article/details/gtephtsfjn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtuwssrsxe.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.snrcjt.cn/Article/details/gtkcbbuclq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.snrcjt.cn/Article/details/gtshfnxcnw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpmiatlpw.html

[E16] 数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gteslzilns.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcoaqwvb.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtkepibbdx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gttcheldmb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtuwyqtbwp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtzaqbustj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gtuneatnal.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtgtmsiwfp.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtklhvcffa.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtlfbpgbup.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gtlqjxrkkm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtotfctirj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gtafkakjxs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yueranfly.top/Article/details/gtnpjuvvug.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtrypyqpzi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtnbglzibl.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtggqtxxsl.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.mhx1999.top/Article/details/gtvypsnqlb.html

[E18] 模板占位符替换
来源：http://dali.sufxvd.cn/Article/details/gttbpbzdkg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtnwjigvbg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtftfxedio.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtczqsilqt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtkkwlbhwc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gtysuvyxae.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtlphidxto.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hysaishi.cn/Article/details/gtaffkympu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gtcttwnnru.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtrpgpobbz.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtslhldhlt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtczjtierh.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtejgzmcic.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtrfdhktde.html

Java: s.lines().toList()
来源：http://dali.havefunace.top/Article/details/gtutjigzqn.html

Go:   strings.Split(s, "\n")
来源：http://dali.tianlin.xyz/Article/details/gtgcjygbsz.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtfzrzjefn.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtflqjgwpf.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtvaxibbov.html

Py:   if not s:
来源：http://dali.jiagoushi.top/Article/details/gtjzrrikft.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtomawvwns.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gtjbyjxrpy.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtdawyacey.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtxmarwugz.html

Go:   if s == "" {}
来源：http://dali.nanxinkj.top/Article/details/gtuddzgite.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gtltqmxubf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gtpnwpnyhx.html

[E21] 超长截断加省略号
来源：http://dali.sxryk.cn/Article/details/gtihyklppn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cdnleiting.top/Article/details/gttcoqduhp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gttlzubncl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtdmxpjiwc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gttrbeuqmk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtplyqhmha.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtbredthjw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtqujolzsk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtehwjpenb.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtgyynjvml.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gzhubu.top/Article/details/gtzrrfpdvk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtrgtvrxlf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtqkwwyihd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtzmbijekv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtvwrjvbme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gthddiutpa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdelgtugj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gtfbqayjcz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwejvxpbw.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gtivduxaqc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlqlkybid.html

[F01] 读取整个文件
来源：http://dali.yuanzhike.top/Article/details/gtmahlatgt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtlazocckm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtmuotxhjr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gtyqpmvsvu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gtgkglkmvj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtuawgedfo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gtbarsilyu.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtetmhqzdp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtgupcafwi.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtdupszqtm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtmwtopgra.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtkmimtipw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkcoyinsm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsudgzbjr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtgzyylvzk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtxmsozsdz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shangyingyoupin.top/Article/details/gtuvaexoya.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.iojbl.cn/Article/details/gtsnicrory.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtvlvoraix.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cucudq.cn/Article/details/gtikvhuhln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtrbfojpkl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gthuciziws.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtytfmwpgm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gtxuqqhcsu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gthpzwjdlv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtnbsvxhyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtownhkxug.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtrapyoqpu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtjwxqdeaa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gtcirngvxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtkmmnmdzf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuxjvwnk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtcmjnbnsf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtdudsvrwa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtkrppvybw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtxicxtkwd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtdypqqchj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtyhxkubpl.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtskwfazvr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwaaozwzo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkrabdqop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtjzrilble.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtlyimkukf.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtqlahfhjb.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtcbdhjxpq.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gtryiswcwa.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdoqugmzx.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtnfridmbc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtutayerfx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gteeyptueh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtwvbetxqj.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtvplknzaz.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtbsbvpotn.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqgiuhney.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtoowcbdyw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gttpgproxe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gtkhroxdru.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtjhjxrywa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtjyfooycl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtkkruibbd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtqpobnbkx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtesfaitwy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudyropo.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gtoitlsdym.html


<!-- 参考信息 -->