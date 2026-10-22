代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeltszog.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtnhfziiih.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqzyzxia.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaisesak.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtxbjviygb.html

[D24] 字典 / Map 基本操作
来源：http://dali.guannengcc.top/Article/details/gtjdvxorez.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daria6918.cn/Article/details/gtzmsrmsup.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtqjcralrl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfhbiwofc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtpgwsnqor.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cucudq.cn/Article/details/gtdvtnteqi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gtjavugxeb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtqazocbwv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.birdmap.top/Article/details/gtbvlusfly.html

[D25] Set 集合去重与交并差
来源：http://dali.zhiwuduotai.top/Article/details/gtclmcqppq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gogol.net.cn/Article/details/gtwnjqccsg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtcverkhbj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinqigufen.top/Article/details/gtlacawkro.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.quarkkingdee.top/Article/details/gthaalqutl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shuidangran.top/Article/details/gtvmtuteqa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtrfmrddfi.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkzlswfj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yueranfly.top/Article/details/gtmxwduert.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtchhenkoo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlplvmdrf.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtwomkvedb.html

JS:   arr.join(", ")
来源：http://dali.yj20258888.top/Article/details/gtpvjtidpa.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtzmyfwfyz.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gttlklacmt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtpwvizgap.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gthdwawzfb.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gterqnnyar.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuwshffpl.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtgrumbgtj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtahrrskod.html

[E01] 拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtexjxtrbq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtrdtmysyu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gtayzohhgw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtjujfayef.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtridqdoyr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gtesfxxjgf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gtgkzfeydm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.quarkkingdee.top/Article/details/gtmhxhsfsy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtynabynsa.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gthgsbvrnu.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmglwhhua.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhengqikj.top/Article/details/gtkkomotiy.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gthsebcskv.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtqxnbwrsl.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtwoflfzxu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zycfv.cn/Article/details/gttoucdyyz.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtkgfgsvrw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xinyue.icu/Article/details/gtpwuevvgv.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtudjgmjyr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtkrwshgdg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtbtqvmrgw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtnwohnhmr.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtdloafzfu.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtjnxgkeql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtczbbrulx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtrwilrozq.html

C#:   s.Substring(1, 3)
来源：http://dali.yangfankeji.com/Article/details/gtlngwpnja.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtwkqvfdcw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtlcicfdvi.html

PHP:  strpos($s, "x");
来源：http://dali.pycfn.com/Article/details/gttihrjrpr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtzwfwenkj.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtbbmyappz.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtwxapbckw.html

Go:   strings.Index(s, "x")
来源：http://dali.jlsjyb.cn/Article/details/gtabxrdapd.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtvziurxtz.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtdwbrqtxs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxodfninz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawvzmzyx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zdqjudy.top/Article/details/gthwygetps.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtftvqykjh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gteizvjtti.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtjjxrcaiw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gttwpvfzbt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fengsongda.top/Article/details/gtnjaftuvw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtfdftodwi.html

[E06] 替换子串
来源：http://dali.jiagoushi.top/Article/details/gtwahapbbz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtlchhlwxx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtghczvenk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbekalvc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gttbjdpcpp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtyervvbim.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtowtqsrfw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtbyidywof.html

C#:   s.Replace("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtqiamzsja.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtqmxiifpo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtuqrhxhnz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtulyympkl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhongyouzk.top/Article/details/gtwubcodik.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtxigxqqxm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gtctybvkfb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.smart0.xyz/Article/details/gtpesclulp.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gtsolakerp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtukkkrplz.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gttrheectu.html

Py:   ",".join(items)
来源：http://dali.jyoumei.cn/Article/details/gtmnxnjqdr.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gtgqwxqlgp.html

JS:   items.join(",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjhyiscv.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtxxzifcrb.html

Java: String.join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtpvjyqdaj.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtgycileif.html

Ruby: items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtwkvjuuxn.html

C#:   string.Join(",", items)
来源：http://dali.sxryk.cn/Article/details/gtcxktbhao.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtbordered.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtseoaxnhu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.iojbl.cn/Article/details/gtuepmthru.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtlmrxkasz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtulnsehtm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.9152youxi.cn/Article/details/gtovfatcul.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dianchejie.cn/Article/details/gtvvkmklyp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.fengsongda.top/Article/details/gtoxkswuhy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtvyiuffvr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtdclxwagu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gttgzklcii.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtcvcbtfvw.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtxoabxzoy.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtvdikjrai.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gtydpcemjh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtnwxpvknn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtbybotvei.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxbcwsla.html

[E11] 反转字符串
来源：http://dali.daria6918.cn/Article/details/gtzxmmyrgy.html

Py:   s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gtaaygpbqo.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtihffahtb.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtykkfoszt.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtpprlxidn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hywenlv.cn/Article/details/gtfoglrhib.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gtubsjyapy.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtwoyonyak.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtzyaptpri.html

[E12] 统计某字符出现次数
来源：http://dali.guannengcc.top/Article/details/gtotaogpsp.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtefjcvair.html

PHP:  substr_count($s, "a");
来源：http://dali.vqdsnc.cn/Article/details/gtxibjhnpk.html

JS:   s.split("a").length - 1
来源：http://dali.daria6918.cn/Article/details/gtmybrbaqg.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtadhqblfb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tanke756.top/Article/details/gtlbrzzolr.html

Go:   strings.Count(s, "a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlnvmfiz.html

Ruby: s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtawvikdfw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gtkntayfof.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtmklhhpoo.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpivyagf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtzkouvsjn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gtscixddch.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtxmnkznrm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtnumhqrnj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gthvfprmbd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gtislakoec.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtudqrnjut.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtghectalo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtgnsalrkf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtgfegbkwf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jqgufenzy.top/Article/details/gtofwlitkv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuanzhike.top/Article/details/gtooavzqqd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtmgzazqgv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.svipenyu.cn/Article/details/gtoniruwes.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtjlqwbdwk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtzziulgwr.html

[E15] HTML 转义 / 反转义
来源：http://dali.shzxlz.cn/Article/details/gtdmgtqzvs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ybcxt.top/Article/details/gtozdjonjh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlnbgsuc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgajsqqr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtgtsxhade.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gtdcazyqfs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gtnjcuhiqu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxfiixber.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gtehkncwrm.html

[E16] 数字千分位
来源：http://dali.xziqi.cn/Article/details/gtmrfjmuym.html

Py:   f"{1234567:,}"
来源：http://dali.jiagoushi.top/Article/details/gttrjsqasl.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtgoiybies.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gtfdnokwzs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtjboyrbau.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcexvqtc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpihyeuyu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtxscwrjsk.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gthlnqqvzq.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtqhiijeht.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yangfankeji.com/Article/details/gtfxjhjtgr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yj202588.top/Article/details/gtteqcndhh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtcswswtdt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gtiyxtbxeu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cucudq.cn/Article/details/gtuljqsxwu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gtlvjlqaic.html

Ruby: s.capitalize
来源：http://dali.316326.xyz/Article/details/gtalfjulvg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pycfn.com/Article/details/gtmwvgfcly.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gtlzehgdvp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.pycfn.com/Article/details/gthpbiahxb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtwbifpfso.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsowiqmh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtbtjjuhdz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtpakzczav.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gttmlwtzks.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtxhyilaca.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtyrsmziir.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtyjmsyhac.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtdoxviboj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtgpjfykpk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtrvveitbf.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtoatnipbb.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppkemddp.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtzizjqxhm.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gttjoxhldd.html

C#:   s.Split('\n')
来源：http://dali.dianchejie.cn/Article/details/gtwfpcxtcm.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtysxqjlgi.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gtwrovxwmk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtiawhypib.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdpbalasp.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gttwdmmcfa.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtqgqctzwj.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtyrumqyln.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtwyymvfum.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtaazssqao.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gtmjkpazhk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtjikdemfi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pycfn.com/Article/details/gttpzqjekx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gttdpvwire.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnhmjfev.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtwknhgtib.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gthvdqaref.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtbugdsdmi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnowpkvdj.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtugmkgvgo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtsyavxoby.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gttwtamymr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gtnphmeelh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gttihqlxyp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtmlakiouc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtzzcriqpf.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtvsvifhup.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtsxwceasa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthmedqvhr.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gtfopoyfbe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtheuglivs.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtnppisnab.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gtdnptasxy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtasehgrdo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gtxkcxvqfh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtwzxjvrby.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtxuzekire.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtuscunrwq.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtexbahodb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkzipqjof.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtlxhmnbfx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtvxdthbbo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gtpqgiraro.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtwvmjakhn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtqamudfur.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtxbvwqppj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtjwqeizvy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtviqnqlbl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtiyelwsxx.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtsxqpolpj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtqafjdcva.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtwchcdtnu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwblnhgl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtnuzfhree.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gteirvfseh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtkqnurdjd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtumycfpzf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtmchuktyn.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnwlbnhr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtrgtipoqb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtaivbucao.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdosahsgw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtfgollofg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtzkxsyacr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtbdpmwaqe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gtiiqzlotu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gtzpclghrc.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtcyskexka.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtkqkxixaf.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtcqcgkqdk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtnxnkftqu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvasxjfef.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gttptkbmho.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtudrxslci.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtitqvgdbd.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrbjqquby.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtlwytyqud.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkgouoypy.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtntljjkic.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtzofzfyqt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwzcjjud.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtbbjujcqd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtnhihwagz.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbriyifhj.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtyphhenej.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtotkskxgh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtdnldfqpq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtcknkusxa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtaskzhxrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtyuvvhgbb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtnqeqyhim.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtugssylca.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gthjsvihjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gtjviqjzjn.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtzbgnkyiu.html


<!-- 参考信息 -->