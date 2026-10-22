代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtryygekkq.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtkhvulnnx.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gthrnsxvdq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gthmwsstdw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvljesywj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtowwsvzlc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gttlnqmkyt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtrfcwaexc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xuanzx.com/Article/details/gtvuyuvwxx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtydnibadg.html

[D25] Set 集合去重与交并差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuwluddk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shzxlz.cn/Article/details/gtjiywmepe.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtthpvncoq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtbkommyrm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtwbojkvkl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtfipwpdhr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuanzx.com/Article/details/gtgmxauqbx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gtasdhespz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtdpdenola.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtgnveivuk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hysaishi.cn/Article/details/gtbhbifppv.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gtoaluusfw.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtqcxmbpfu.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaajhwlbm.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtjilhuyyz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.birdmap.top/Article/details/gtbjpflrws.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gthqopqiuv.html

C#:   string.Join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gtnpgawrup.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbiwytybj.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gtstvnvnio.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdabxpiux.html

[E01] 拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtzcmvmbps.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gthinbtdko.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtqmcrwacu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gttciiiuoe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gtahuknbvw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfemmpnkc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtohynhjkl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtkwciysdl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtzzkppmmm.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gtfyqdbtog.html

Py:   "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gtiulakjoa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtyqmbsfxi.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtmthocacs.html

TS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtpeqnawzf.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtagqggrgb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gtilemyvsb.html

Ruby: "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gthkeaegyz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtzpuwvrwm.html

[E03] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtxrphcojt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gthccabsnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtnfoxwpoq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtelgkagir.html

TS:   s.slice(1, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwoxdjvk.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtihbnzjjv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtjyphtqma.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtfrrbzfdc.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gtwablvmoh.html

[E04] 查找子串位置
来源：http://dali.gotoacloud.top/Article/details/gtkcwpstrz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtpvtdpmkt.html

PHP:  strpos($s, "x");
来源：http://dali.zdqjudy.top/Article/details/gtelgumaey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.c1oappe.top/Article/details/gtbdezopve.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtygiltlpb.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtfgudjedv.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttofxaucf.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtenqkpnxk.html

C#:   s.IndexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtiovfszex.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ehwqpu.com/Article/details/gtkxkbttso.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gaohongyu789.top/Article/details/gtuccmrvtk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenzaomai.com/Article/details/gtafceixny.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtaflwcfra.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.316326.xyz/Article/details/gtdcgxiwtv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtidlamozn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.nanxinkj.top/Article/details/gtdimofwlz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtlgcxsvhd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtohpwhjrl.html

[E06] 替换子串
来源：http://dali.redwolf501.top/Article/details/gteefxcsov.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtuhbvphgf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtdiykxyzk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrefrelrw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtekhwclqt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtetwmlhde.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqhfuojz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtdidjvl.html

C#:   s.Replace("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gthscenxna.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtocszgjac.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtyzkcdium.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.guannengcc.top/Article/details/gtmehhvchz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtudcjhhuu.html

TS:   s.split(",")
来源：http://dali.meibo888.top/Article/details/gtjvsjomuo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtvxyuzdoh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtqfyjcpyv.html

Ruby: s.split(",");  s.split
来源：http://dali.meibo888.top/Article/details/gtedxbdmij.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.pengpengdd.cyou/Article/details/gtaxvretar.html

[E08] 数组按分隔符合并
来源：http://dali.shzxlz.cn/Article/details/gtcgtdvilq.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtgqjhkerp.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfuyxlda.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtxsozaaup.html

TS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtasgffzdj.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gthevieame.html

Go:   strings.Join(items, ",")
来源：http://dali.ydzc1.top/Article/details/gtkgcwmbsz.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiavwxwl.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtauivauie.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtetvgjtag.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.svipenyu.cn/Article/details/gtfyxvsdgp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gtcervpgwy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtklseimbo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtqwkjkidr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtzzxasbpp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzybxnncd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.havefunace.top/Article/details/gtknnmezjy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hammf.cn/Article/details/gtpbfpujqv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jyoumei.cn/Article/details/gtogbnxmjf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjscufftk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.kuanghao11.cn/Article/details/gthfgiewyg.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaknlwtt.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtzkpisxzh.html

Java: String.format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtvxiiozeb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtyanlhule.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtzyaplzak.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtiaamcpuw.html

[E11] 反转字符串
来源：http://dali.dianchejie.cn/Article/details/gtchwwbwgn.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtieqgnszy.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gtvawuaelt.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtkrropdqq.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtldrpvnaj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtrykzkwwy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtvfzueovh.html

Ruby: s.reverse
来源：http://dali.ybcxt.top/Article/details/gtczsbzmkx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtkneyalcw.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtqucyjeba.html

Py:   s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtdaiyupwn.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtmotirzzx.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gttctaajav.html

TS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtfjqutngx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cqqwz.cn/Article/details/gtpfcuimiw.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gtsstdjqun.html

Ruby: s.count("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtdhyttxot.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hongshengwenyu.top/Article/details/gtjxlitrvz.html

[E13] 逐字符遍历
来源：http://dali.cashguo.top/Article/details/gtzirwkazg.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtoiejktvg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnxiangtu.top/Article/details/gttysmoohf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtkyfyqpdx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtljiwibuz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnqzz.top/Article/details/gtgaynhuim.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtvwbxkfgr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtpwjtvqwa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtweimueze.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtfiwwjssw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tanke756.top/Article/details/gtwixtgame.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtmogbqorz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.haohaochexian.top/Article/details/gtfuxlbqmd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtlzeurpic.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtxtmzakxp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gtszgqrnoy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtmobpmfqa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtholscyto.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gtzrdwqvyo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdghcqgl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gthhdqsnwf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtlvcnrlds.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sufxvd.cn/Article/details/gtphfiahkl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtlktqfhny.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuxming.cn/Article/details/gtbfordtsh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtghswydot.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gtaiyxwlta.html

[E16] 数字千分位
来源：http://dali.nwbrower.top/Article/details/gtsqctsjim.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gtshyfvzpp.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtqtqwfkhe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtckpbeesp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gtvafxfjpz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtxlruyupa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtujuipzwd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtmnfpsnpk.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gtabbaxspy.html

[E17] 首字母大写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaseidky.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtddxankmy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtbgtruxsn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtudjvlnmt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gttwcthnxd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj202588.top/Article/details/gtdqvsowic.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gttfqknhli.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtefjltnkq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.haohaochexian.top/Article/details/gtfmkjrpvf.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtqiehctry.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zdqjudy.top/Article/details/gtwzswrcyz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtgndbofvf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtjurfozsd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtpybpzvkv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gttcjitrte.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtxznsgytt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtxblfecdp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtjpgumuhh.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gtllwobshu.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gttauxcdlo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtajfstcmn.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtuukgnbao.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtalonyrtf.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtvvqwmjst.html

Go:   strings.Split(s, "\n")
来源：http://dali.hnqzz.top/Article/details/gtqrzucnsb.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpficfcw.html

C#:   s.Split('\n')
来源：http://dali.gotoacloud.top/Article/details/gtlvpfoioq.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtisxnefiv.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gtfcwqfruq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtgtwamzwy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtjyhtcpzc.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtyugfkujl.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoncwhnb.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gtzlcgemsi.html

Ruby: if s.empty?
来源：http://dali.jianghu66.top/Article/details/gtnckbqcyl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtkhyeglxf.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtmexnxhje.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtvbdvjhwj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtbvnbylos.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtadvwcwmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtejtfwaca.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtmodahbvr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gtmpdhyslk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtmzyauzqg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtofmmguel.html

[E22] 字节长度与字符长度
来源：http://dali.shuidangran.top/Article/details/gtisgupbpr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gttbmqlwyh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtfwczmksl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gtkesdxlkw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gthljshnzf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtavlwhhcs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gttqzurkeb.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtyorrdjfr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtqhvqalao.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdfrsmfut.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gtpflxdxcr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjaditdyx.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gteldunrra.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gtzcebpvcn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtncvtzoqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbpynapk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtwrxknffw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtfniqnegn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258.top/Article/details/gtarnqbvtu.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtjgtgswoz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtozjngflp.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gthfampmrw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenlongwang.top/Article/details/gtiuoxrvpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtdjxgdhyp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtrbcjpxae.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtuvfomjro.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtqxomthna.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtrtrhvrvm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtqgfqtsiu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtgmhvgjcm.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gtrwrzvtbw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtaejefpww.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtajxzkngl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtipzbxsds.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtkzuvrzbw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gtmkwnepzy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtjoudjsdc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvghhoctq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtzvdmtapa.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtecbwwokl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtetgszoxs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtjxpdxdfg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtdllmghbv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtikbcpibd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtjrwxsyxt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtvjdswxkk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtsoooaxld.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtulsukjda.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtvkvrbwhl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gtaimqytxp.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtuzthtivf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtuwyqwvju.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthlwuddja.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtudvmewrj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtzuaykbvg.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtilabpcdl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftwryfvv.html

[F06] 删除文件
来源：http://dali.ppjwa.cn/Article/details/gtxtuxxruq.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtigidivbq.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtyijuixin.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwsqnwdzd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtmxmjsulj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtrnldapdo.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvuhquabu.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfrqrivgp.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtrcbqrtlq.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtgzwqrcan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtkhdykbaa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gtmsqicazv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gthuvjnvda.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gthsmjifnv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtonquvrla.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gtaleydlos.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtudpivlxx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtobmaqqtn.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtzqsmytnw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtewlqbkak.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cdnleiting.top/Article/details/gttxazdtyl.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgglxrgf.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtqdfoimuy.html


<!-- 参考信息 -->