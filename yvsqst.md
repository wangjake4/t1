代发 wailian999

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtnvyewawe.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gtmtqvlhnj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtnxlmgmlo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtkkvhddai.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtqlxrnpdr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gtuhxhcdsk.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtskmwiton.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtmfifsosq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gotoacloud.top/Article/details/gtmdylngpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.vqdsnc.cn/Article/details/gtedpdsfil.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtlpdxxjfn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtidwdsnyj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtgcjffztr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtrruniohn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtnbtyufzf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ivvv.top/Article/details/gtibkjehxh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtjovkutdz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtgnqfpvqh.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtyvyiepmq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtljerlpkh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guannengcc.top/Article/details/gtfxlijetv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gtdzhikgzs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jianghu66.top/Article/details/gtivxsrgrn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ydzc1.top/Article/details/gtwiokpsea.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zycfv.cn/Article/details/gtuwefdyfq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.redwolf501.top/Article/details/gtlygusawl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtmjenbvuv.html

[D26] 数组转字符串
来源：http://dali.redwolf501.top/Article/details/gtncujwjhs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtpylsmeya.html

PHP:  implode(", ", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtidtiedeu.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtvpnwcopu.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtdofnhazn.html

Java: String.join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtfngfeken.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtuefskdnu.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtdjypdfwh.html

C#:   string.Join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqovrrfi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtkhhcpobt.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gtyakznzgn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtygaqlvod.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gthgxgsqlk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gtenlpfhhz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gttwljxfbn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtjasrqqom.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtpzngbgvr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtjvoquijj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtflmefjeb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtlsgnzbbm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtblutsybz.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtmucqfjhw.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtjehgnbqz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtaoeenarh.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gtskavvzpa.html

TS:   "ab".repeat(3)
来源：http://dali.yuxming.cn/Article/details/gtgosmwqee.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtnajkxxvu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgufenzy.top/Article/details/gtlecdlehf.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamjfpzhc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtoninpqax.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtykzdoiun.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtqcuzmbje.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtadlyhjqb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtzgemtcgh.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtikaxkucq.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtnqzzzdtv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtxloqyngr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtjjgogaez.html

C#:   s.Substring(1, 3)
来源：http://dali.bjfxy.top/Article/details/gtvgsagibh.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtftdacpbd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtxfsmzthq.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtxfgjuntb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gtvgmllwel.html

TS:   s.indexOf("x")
来源：http://dali.hywenlv.cn/Article/details/gtsacrrexl.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtzjmdbhco.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtozkrumlv.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtfglyymuh.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258.top/Article/details/gtdxnrdvdm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtpihbmbth.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tianlin.xyz/Article/details/gtghgaekxy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtkmkwjobz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtkashdwmp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteekmffst.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvplsnix.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.pycfn.com/Article/details/gtytesamku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtvuslgvte.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yonumen.top/Article/details/gtefvepyur.html

[E06] 替换子串
来源：http://dali.daxiang520.top/Article/details/gtxtmbhomj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gzhubu.top/Article/details/gtroqpvwoa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtphmfgvgr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtsixybihr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gtumbaqkgi.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtgnfbvtrt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gtcejbjick.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgynirweq.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxolgpltt.html

[E07] 按分隔符拆分
来源：http://dali.hammf.cn/Article/details/gtbidglkfb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cqqwz.cn/Article/details/gtmxqzcvgd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtsgcbfklb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gtsmchapsx.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtyshddemi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.iojbl.cn/Article/details/gtzwmgzesi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zycfv.cn/Article/details/gtaqmyilob.html

Ruby: s.split(",");  s.split
来源：http://dali.shzxlz.cn/Article/details/gtzgmfewrk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yueranfly.top/Article/details/gtiiiuygjt.html

[E08] 数组按分隔符合并
来源：http://dali.cqqwz.cn/Article/details/gtztgnpano.html

Py:   ",".join(items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcsgksqp.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtebnmrvuq.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtyepyxisn.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtvihqqreo.html

Java: String.join(",", items)
来源：http://dali.fzhhl.top/Article/details/gtrjjjfnyn.html

Go:   strings.Join(items, ",")
来源：http://dali.xuetiantiany.cn/Article/details/gtnjoxgnmf.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtdaunuwav.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtfszzctcl.html

[E09] 去除所有空白字符
来源：http://dali.ydzc1.top/Article/details/gtdbgszama.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zdqjudy.top/Article/details/gtipltppug.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtjfbdwczi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtgnucaggx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtmovfrcrg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aizwys.cn/Article/details/gtsthanboa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtjdxmlzij.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtyxlropkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yonumen.top/Article/details/gtywslgsga.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gttasqvrrm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtfcmioxja.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenzaomai.com/Article/details/gtpunhenwf.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtwmlsivnf.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtggmzhsja.html

Java: String.format("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtpkjzfubx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gtappclvez.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtrozgwuqc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqduabof.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtlbpmrdin.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteqkvoav.html

PHP:  strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtfmncebka.html

JS:   [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtgqchpgqg.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtyfajhfkm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtxxizhqmd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtulhscfxn.html

Ruby: s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtoxyceaii.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtpfvrffgr.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtqjeuznpu.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtcoxhxwke.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gtushsezty.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtqhhadajf.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtvxomjtrr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtgpfnnudu.html

Go:   strings.Count(s, "a")
来源：http://dali.pengpengdd.cyou/Article/details/gtsyjucyyk.html

Ruby: s.count("a")
来源：http://dali.xuanzx.com/Article/details/gtmkgzskul.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtlgihmadm.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gtcipjtfjo.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gtaosvogad.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gttlbuides.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtbxsyaszo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtseabudhg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ehwqpu.com/Article/details/gtnaystsyi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtdhxcmutr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtepartlyc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtkvsaggkv.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtludbhwsb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtpaqaiqpp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskkdcilc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jianghu66.top/Article/details/gtpnioirlt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzrvrqnzj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuavntib.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gtzhzonnev.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.pengpengdd.cyou/Article/details/gtnpyxhfeg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtymorcthd.html

[E15] HTML 转义 / 反转义
来源：http://dali.tian-w.cn/Article/details/gtatwnshgy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258.top/Article/details/gtrwhitthl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zdqjudy.top/Article/details/gtfkbofqjt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtrbbwfccs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.tian-w.cn/Article/details/gtpshexzfo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gteimlhivm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtdqltnewy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtujgecaxs.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtnliejfim.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtakdsdpqz.html

Py:   f"{1234567:,}"
来源：http://dali.yuxming.cn/Article/details/gtccepgrwh.html

PHP:  number_format(1234567);
来源：http://dali.hfpthk.cn/Article/details/gthzrfpejq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtigsgevkw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtuxphenvf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtcscbxxrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gtnxyeshiu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtsrrdfufr.html

C#:   1234567.ToString("N0")
来源：http://dali.chenzaomai.com/Article/details/gthywhpgid.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gthfgumlhz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtrkoobrtb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gticpevucg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gtyafngttw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtjpjndade.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtrfdmjlnt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtprhqsqqi.html

Ruby: s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gteeyyiubo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtzfclkent.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtxxwtxolh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtoaoeebkg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gtifckncgu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gttycckhqv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtqonqwxkg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtnbbllevu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gtecuikstg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtzapmfkrs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nwbrower.top/Article/details/gtuhqpfvqy.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtwvgwbney.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtauwylneh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jianghu66.top/Article/details/gtdzjgtcrc.html

JS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtcekhmbzk.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gteaysxzts.html

Java: s.lines().toList()
来源：http://dali.sweek.top/Article/details/gtyhxnbuns.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtfxwgviqt.html

Ruby: s.lines
来源：http://dali.xylfe.cn/Article/details/gtpmmbkqed.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtoihwxfwc.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtrtnmryhl.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gtpvsdedfy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsdqydpc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gtluotlbyx.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtiaagdxlk.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxjvvljel.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gthrukfngs.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtjfscraqj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtaolioolb.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gtwkkjcpqr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtyjfrzipb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtxhigjogb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gtsoxfqapo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtgucmersl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtyizzntir.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtexpjwvro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtvilvrkpy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtuywugzdu.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtftimqaop.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtdxrbeypm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtgyyxxkof.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtdkudoquy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxuhefvt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtwhywcvxg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtzdqiuqrs.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtnxoxrdwj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gthiluuiiz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqiwajvfm.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtstheoowo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqiqrnzny.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gtmdegpwjl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtsitmbirc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtmzmzvtdg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gtscjamxej.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtemlwrjwq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtwoafsnis.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gtzsyrniks.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgispseag.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtghsjumwv.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gthgtxcldh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258.top/Article/details/gtqpjixuut.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtkttpjava.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtjcbosuek.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtshdablcj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtkdtrsqjk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktzxtplq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtcyrscnch.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtqxpkxdue.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtmjccpdyg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhixingplan.top/Article/details/gtpiiotiue.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtgpvgcovf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtrtghhzbw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtlivfknxa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtwevsowog.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtpbsvgzhd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtiqmqlkmb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtisscshxe.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtvzszufsr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtlldnwfod.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtdpmcjykc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtxuhvpidz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvmujqra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gthtcelljm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtuwcqfioy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtrrvtrhgs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtpnxrxhid.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtnrmtqggz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gttldpkdkz.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtluvrkzfy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtlofoisua.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwudbuytt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtznhfqcvr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtveawbvfw.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdmasvxfr.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdgmllqhe.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtwzvxxtnc.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtybnwztwg.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtgmoqanfx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiogphsip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrqmbhhoe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtuvdsosvv.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtolmspihg.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlvmvvyiq.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtvjbjrcqm.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gttsmnjkvv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtgicemjak.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtbmsdsxep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbpqkrsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtsttgitpd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtdpxjwaez.html


<!-- 参考信息 -->