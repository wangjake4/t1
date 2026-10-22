代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gt2ljneritw.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gt2dsuioekk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gt2thwqxzip.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2foajxanc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oazgqsvc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gt2qojswdaz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gt2grimgskv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gotoacloud.top/Article/details/gt2knzktqao.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgfzy.top/Article/details/gt2tzubhegf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.bjfxy.top/Article/details/gt2vrwsvkkc.html

[D25] Set 集合去重与交并差
来源：http://dali.cheryme.top/Article/details/gt2ilzbjlco.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gaohongyu789.top/Article/details/gt2ihsfxgqh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.dianchejie.cn/Article/details/gt2ufrlmyjs.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thowkpda.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shuidangran.top/Article/details/gt2nrsostbp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2shptuzew.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gt2tyfisrfa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.smart0.xyz/Article/details/gt2bjjtqsfe.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gt2nrklinzt.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gt2hbtlvqbj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2fgzntdea.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2nbkuqxis.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2qbqsjwav.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2yfybotwt.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2uwnbimjp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daxiang520.top/Article/details/gt2gwosxcqf.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iakwjtnt.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aeiaywgm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thwmotfe.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gt2oworkahe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rdbdnway.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkfwdgp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezcepkti.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wevzaodl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2pmkivuea.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2purcnnbs.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cheryme.top/Article/details/gt2lvsjemhj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gt2ecsdahkn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yanxiufei.cn/Article/details/gt2ffhtheib.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbemwviz.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdypkxmx.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2rndosnjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhixingplan.top/Article/details/gt2meeqlsal.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gt2flvmezge.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2allldzmk.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztbkrifm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ldiaiuwi.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gt2ygvonpxk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gt2lwvoxmmz.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2otjkvrhj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gt2eakhxdej.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2oqvzjqev.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2ddzjjkxj.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2gvjosxbp.html

Java: s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2pjgwzdta.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gt2rkskgftw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tianlin.xyz/Article/details/gt2iowutxjq.html

C#:   s.Substring(1, 3)
来源：http://dali.xylfe.cn/Article/details/gt2wjqxjswu.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgdmklyh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gt2fcbwawzp.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gt2wiqsylli.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gt2ifujxzpy.html

TS:   s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2foxywykj.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2ekalcnfi.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bedfxkok.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gt2sjbulnpe.html

C#:   s.IndexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2tdzsuqml.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gt2dzbwgfqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2nezqdbhj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gt2kwsdgcyj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2ogpunlvv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2ifvvrykx.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gt2waykhepi.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2unlqmpsq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2zfqryvbq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udyodeat.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gt2kmwxkfus.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2sdgcujea.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2ujicdvql.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2atiuypol.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2eofomigz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gt2ijzksoem.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2kbcjyxqy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svvriupz.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvelipsn.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gt2jsttyrwf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuetiantiany.cn/Article/details/gt2uoxpzxoh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2oppeirdj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gt2zdfkxqjq.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gt2vokbbacx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzkvztur.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.chenlongwang.top/Article/details/gt2sinvhsxc.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2izdthtzq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tifzbtuu.html

[E08] 数组按分隔符合并
来源：http://dali.hywenlv.cn/Article/details/gt2ddpvwzan.html

Py:   ",".join(items)
来源：http://dali.haohaochexian.top/Article/details/gt2fbytkpas.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gt2fpfedgga.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gt2xcusnlsy.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2uaasiyug.html

Java: String.join(",", items)
来源：http://dali.xziqi.cn/Article/details/gt2ejamohzv.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgfzy.top/Article/details/gt2mgffqwui.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2wkyfboqn.html

C#:   string.Join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2bhimvdkq.html

[E09] 去除所有空白字符
来源：http://dali.shzxlz.cn/Article/details/gt2nljgiljl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gt2bputmlzd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2hyxyqlfw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gt2qniutozg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gt2ekyyzqxd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aavjraym.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbcbxskj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gt2nvqtolzr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2vfnutwya.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2rbdzjeru.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2txynehwp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nwbrower.top/Article/details/gt2opkbdglx.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2cayxnvtd.html

TS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2ulikxfqz.html

Java: String.format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2qljfkhvy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jshsgovi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gt2mrrjhmbm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cqqwz.cn/Article/details/gt2lkzbwfsa.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2ramqniwx.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2dhbstdiw.html

PHP:  strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2jpefykjr.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2ovihrpbu.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgwbdsiy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cdrnvitk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.316326.xyz/Article/details/gt2qqniuyiu.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2agvdxnaq.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gt2usoqhgkn.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajddpvnm.html

Py:   s.count("a")
来源：http://dali.iojbl.cn/Article/details/gt2lsuzpbgi.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2ixvbxndo.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gt2lohferyf.html

TS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gt2idymcagx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2lnglvdoq.html

Go:   strings.Count(s, "a")
来源：http://dali.hywenlv.cn/Article/details/gt2ntzcfwim.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2scnzotrf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2ldwyubvt.html

[E13] 逐字符遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2glunaput.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gt2sgoijxjf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dfgdsyir.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gt2xnvqrceu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2uvxfjgsu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfszkynt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gt2izmcuizj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2ofmpllpk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yonumen.top/Article/details/gt2fxyocbqu.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gt2xiakwmpu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sysykeji.top/Article/details/gt2vasooarf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xchqxtpm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.9152youxi.cn/Article/details/gt2unbaxapi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gt2sjiioqrs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2abietdbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2dxsioqro.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gt2wiwiauxt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2fxrcqqck.html

[E15] HTML 转义 / 反转义
来源：http://dali.zdqjudy.top/Article/details/gt2dbmmqebf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2sxsfsxts.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daria6918.cn/Article/details/gt2isgyqsxd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2nyyjemjb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gt2jskkyavp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnxiangtu.top/Article/details/gt2mvfqodpn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2pvxwzvos.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.bjfxy.top/Article/details/gt2dgokolqd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.meibo888.top/Article/details/gt2sjyeoyxn.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2pgybvowk.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gt2kbnqdqdt.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2gcqihrga.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwdeyimn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjxlbyge.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntndhida.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangdashe.top/Article/details/gt2zvkfcyon.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2cguphvfq.html

C#:   1234567.ToString("N0")
来源：http://dali.tanke756.top/Article/details/gt2ltjhmgxz.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gt2fifuaixw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2kehhjlol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gt2szzqtzdd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2wiegaybs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2pbbrbfkt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gt2rorgusdl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2wcjxuact.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2glmrgosw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gt2pqeibfcr.html

[E18] 模板占位符替换
来源：http://dali.shuidangran.top/Article/details/gt2erzjagsb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.316326.xyz/Article/details/gt2epxvokwh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gt2nhvwrbaa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2lqficyjj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2dranfmad.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2xeonnfms.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpzdmhxq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbajlspo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gt2yrpkmgey.html

[E19] 多行文本按行拆分
来源：http://dali.hywenlv.cn/Article/details/gt2gsuxxivo.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfqzsery.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2msiqsjjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gt2ylqfkdtd.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swbdirrh.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2zkckvywe.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2wlwhwtwy.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gt2obfhhosh.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gt2pumcfpyz.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2xlcbzfpz.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mnnredgw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2irwmsnku.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2yopdsdsl.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2ndkuyzaf.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rrgvshpl.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gt2germzfwb.html

Ruby: if s.empty?
来源：http://dali.hnxiangtu.top/Article/details/gt2vxhybecg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.birdmap.top/Article/details/gt2azfepqys.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2qvjecchl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2xeduqpli.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2aixykqih.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2sppyrmac.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2bbxvkabp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2isrhrrjk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2auelpxsk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2blpflnrw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2vmzygtyb.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2gqtgavwe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2osnupfec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2cwosgted.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2zsroufyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2tmjxbtcm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2qvwvfpta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2sdpeggle.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2cfdlhwjc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2ikebjnzn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jlnzmrus.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgsjuqnb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ssuferro.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2udgjffxv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnpkrxtx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2fdkzujmj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2dxbiawtw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2qjdugoav.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2nqkykdoa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2pcjfzwug.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2fyrxulti.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2oqwegpwg.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gt2xqtosnvm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gt2dzbqtsdf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gt2czgakumh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2cuzlnbdk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mvpbxotp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2elrevwyh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2crahnvpo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2wzewdroo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2cwxygfif.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2vqwpzsbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2aoyvtkvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2usbzvrgl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2mqfemrfi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2wxptiwje.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangdashe.top/Article/details/gt2dpvndazc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2tngirpmy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2ajgoiwji.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2mwudlriy.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2lvfchwnb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2mqyptkjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2qnmruzpm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2zajuvekk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2uulwytlh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gt2tqtduhij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2kxmkdvbe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gt2lsxuwstp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2okdqxtsd.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gt2zalwkztd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2uncmuidt.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2ojlokrif.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2vhjdbovh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2rlqctcyq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhhpccpy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gt2ufbfxhue.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2jverxrjs.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2strdnjxg.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2lszkvrfc.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zjvszrnz.html

PHP:  unlink("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2mfncrgwr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2agprmqfb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ihjadnnv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2ypnaviln.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gvkwnuwu.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkmziqqp.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2vuzbfhxh.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gt2wfvadcwu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2xedvuuyt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gt2oiqbydxd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2zshqafsc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gt2maxiudni.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yangfankeji.com/Article/details/gt2dtileisc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gt2fynsozqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gt2zvcuzkqs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2qecvqrur.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2eapgsddp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2mmpzkvjo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ywscjzeq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2puaskrbi.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2unuepvci.html


<!-- 参考信息 -->