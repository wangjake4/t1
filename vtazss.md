代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gt2qpahkwbh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2gscjmwbs.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2zeoqfutu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gt2jvmdurhk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gt2fqnlictd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2zfegaujp.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gt2hznxaxkp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gt2ljuzymga.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hywenlv.cn/Article/details/gt2pmejrwkk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2islybfba.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruupunfr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sufxvd.cn/Article/details/gt2eoygeiqi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2nsqdapes.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kikbjthn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2xesbyxlo.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2lifwumwz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.iojbl.cn/Article/details/gt2cxqhbumi.html

PHP:  implode(", ", $arr);
来源：http://dali.guannengcc.top/Article/details/gt2dhuvfclm.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2geyoinbh.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2vvngyhmb.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gt2mgxbscwa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gt2djyrubgw.html

Ruby: arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2ykxhcwcm.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2cjgjdxwu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jgsolbxp.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gt2fbsqyoww.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tbtkazwe.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2rschmubo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2mahcnhyd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.guowangkeji.top/Article/details/gt2gbwjlfmp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2xhtsohuj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2ubkgwpfw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gt2qmpkgouh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqrgyieb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2fpizolvc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fboivzmp.html

[E02] 重复字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2gwxilnqx.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2itdqexpx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gt2jwruryes.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2jbdznard.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2comipgcw.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gt2ignpmgnk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gt2shjnicvn.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gt2alhauhxb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2egowhhvb.html

[E03] 截取子串
来源：http://dali.hfpthk.cn/Article/details/gt2zzdbqfkw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2cvfxdacn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2uniwfmku.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2nlfhifse.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gt2wqleilpw.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2cgxbkerq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2dtbifqcz.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jennwzoi.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gt2qvyryptw.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gt2acyidcuj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gt2gznhbcfd.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gt2nwbgmexv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gt2nfbuutkr.html

TS:   s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gt2jqondsqx.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsfasnjf.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gt2tmhausgl.html

Ruby: s.index("x")
来源：http://dali.jqgfzy.top/Article/details/gt2epjpqzov.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gt2gilltmne.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gt2koolshvs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2kvuvndjw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.smart0.xyz/Article/details/gt2qdrovusb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2jljcwyxl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2nvvezxhb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2lqoljcia.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2vhkwudna.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yongpay.top/Article/details/gt2hewnxrde.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.andypj.xyz/Article/details/gt2oumytbsy.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gt2dwranavb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gt2knccjofv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gt2balodghx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2rzbxkkdz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2mnoqqeej.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2gtaufxnu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gt2odajwnuy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2acopjeot.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2evqufxup.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2numiuciv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gt2oqojikxe.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2nyzommql.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2xlpdmwgk.html

TS:   s.split(",")
来源：http://dali.yuanzhike.top/Article/details/gt2szzdfgji.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gt2xuziqvwk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lnztbwuk.html

Ruby: s.split(",");  s.split
来源：http://dali.shuidangran.top/Article/details/gt2carqlhzm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gt2owgtzutu.html

[E08] 数组按分隔符合并
来源：http://dali.vqdsnc.cn/Article/details/gt2xopnohoo.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gt2wjavckjh.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gt2pogpjkud.html

JS:   items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gt2buwiflwh.html

TS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2ngcaujhh.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gt2gbkldjwp.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gt2edwtijqb.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2laicxqmr.html

C#:   string.Join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2mckyatvl.html

[E09] 去除所有空白字符
来源：http://dali.pycfn.com/Article/details/gt2otevsqyj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shuidangran.top/Article/details/gt2ljyguhnj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2awjrcpbt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gt2xovdsgko.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gt2woqxgwzp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zycfv.cn/Article/details/gt2bmkhbhuq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gt2niftjnbo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gt2cserglbz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2bgzevqan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.guowangkeji.top/Article/details/gt2vxotcaxr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2gvnmhqyo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gt2uxwwjuaq.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2qcuxjkri.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxztowar.html

Java: String.format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gt2ufeapize.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2dzhuqxth.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2mgtkijkl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fengsongda.top/Article/details/gt2rxktyqkg.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2kmrmqvgi.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gt2oaplsggf.html

PHP:  strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2aqklwbws.html

JS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ttaurjrw.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2myefebkz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gt2yckrfzcw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2jyrcqgui.html

Ruby: s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuoxynmi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gt2lrcynzjw.html

[E12] 统计某字符出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyvbaujp.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gt2hisamdab.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gt2qsarfpih.html

JS:   s.split("a").length - 1
来源：http://dali.svipenyu.cn/Article/details/gt2rqdyqwlp.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gt2gvlkusnz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gt2hwveaaff.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gt2dvybkdvg.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2avwtkyyp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gt2xsuctfji.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gt2hhqjrkar.html

Py:   for ch in s: print(ch)
来源：http://dali.yj202588.top/Article/details/gt2gstrmrno.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fwqslgus.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2diugoars.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2dubfqprr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2gnqhdeie.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hywenlv.cn/Article/details/gt2zmmpwagf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2dijmepqj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gt2yrjsmhin.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2ullhuqkf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gt2gkhffqoq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpfdyzmf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gt2qicxrynd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2lvaszxtw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2wzohvgnw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zdqjudy.top/Article/details/gt2acafiymc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sweek.top/Article/details/gt2pqjedqfc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2tixzhvdf.html

[E15] HTML 转义 / 反转义
来源：http://dali.daxiang520.top/Article/details/gt2ofpinjtd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2khziyoza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hysaishi.cn/Article/details/gt2jnyjgcsc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqxfxzdu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zycfv.cn/Article/details/gt2gursxpzm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gt2jvyfhgxo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sysykeji.top/Article/details/gt2bgwkqgee.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.haohaochexian.top/Article/details/gt2uiadbdrz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euwcaiwe.html

[E16] 数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2gfwirqjf.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggmxmggf.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2vwjosgln.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2szgzbuhw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lagilyic.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gt2fspswlre.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yangfankeji.com/Article/details/gt2voanrifr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2asxmrobc.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2okdhslvt.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gt2cnhanqvh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.svipenyu.cn/Article/details/gt2nyjmixph.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gt2atozfbqx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2eorvudnw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ejmwakmc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xinyue.icu/Article/details/gt2gfjdvbpd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2hvbxpmww.html

Ruby: s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2bhpyqlmf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gt2otnaznnp.html

[E18] 模板占位符替换
来源：http://dali.sysykeji.top/Article/details/gt2nsjthkvy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gt2insjjfav.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zycfv.cn/Article/details/gt2ubaqdnrb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gt2bytpdcfw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2rchuhptg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2isjravyy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2zhdsuwtf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sxryk.cn/Article/details/gt2nvatdgxb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zycfv.cn/Article/details/gt2nwusmxru.html

[E19] 多行文本按行拆分
来源：http://dali.0kj1m.cn/Article/details/gt2qejtwupw.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2vgngkxkr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvcduhgf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gt2ufjgvbwi.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2zdmnprdf.html

Java: s.lines().toList()
来源：http://dali.c1oappe.top/Article/details/gt2urpojcvy.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gt2yenninvi.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2oarwdwih.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gt2yeylexvl.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gt2egarctsf.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2dqfhtebp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fzhhl.top/Article/details/gt2jqwzswky.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gt2dqhhjnrr.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gt2agwwficn.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2gzycgkew.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rmukrlve.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2rbjazety.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guannengcc.top/Article/details/gt2gagbjubj.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2lxwtkfdo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gt2xblaroug.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2lxcmxypt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2msqbubho.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slbikrxs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2xuqzhtxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2spxgwkla.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2symmjhmx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2upxxobuf.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntebhjgx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2aalxdenk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2anoepzao.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nwbrower.top/Article/details/gt2anxactcl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2fhmzhdsf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gt2ixenluwx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gt2guinrnsl.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2vicjmrni.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gt2olynquwn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2prpziglb.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gt2wyljufbt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tixphicu.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2wewdbtxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gt2glrgwaqx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ysthweif.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2pbrulrpe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2sduituvk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2fwzslaxw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2juwaodrp.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pddbvyjh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2svkxrxpj.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2jnxatrrk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gt2ovqeqcnm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2qxdabwmz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gt2udsczllu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruutnfbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2dpvzyuar.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lluojaui.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2zqhepifw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2knaccioi.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gt2cboebtxy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2ouxpmwfb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2eaklxgtl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2lpblyfgc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2idayiwns.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2luzqpmdu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mojnkgfw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2suigiirv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2gwcomxom.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gt2zxdydolw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ximbwsba.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2uiletpxm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2zgispoti.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2zpoqvujd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gt2bpqmuhaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2bjrhdney.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2esomskkk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2sbefqqqt.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2mqxivexj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rshvwyel.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2etvqovtb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2esqantls.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjumauag.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2tnbvewna.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2grmihkqb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ajwqistw.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjldkvao.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gt2plgqibfa.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2vtztslcp.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2mqoxkwbk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2aokuzueg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hkshqnwk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2qjxilctd.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2fjljlcaa.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2iyuyaygf.html

C#:   File.Delete("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2cokdhblz.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigufen.top/Article/details/gt2wzvaccub.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2qmhhjxhk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2atmobsld.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmmrowf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2yktbjziz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2qxslqyem.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gt2ceceuadj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2wzojycqh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gt2fbeqosfq.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2wdfgavtx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2frwpxwia.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2bfpuzesn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2efudrnjz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2hqccmvxm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2yaygovze.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2kfnoickx.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qykzehoi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2epqlngfd.html


<!-- 参考信息 -->