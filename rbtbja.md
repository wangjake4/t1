代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhixingplan.top/Article/details/gtghhrwmax.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258888.top/Article/details/gthqndsxkw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gttmysexcf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gtxinamtsj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsxqrkee.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtguaklwsl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hysaishi.cn/Article/details/gtitxpgrhv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtzmxoidpb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.redwolf501.top/Article/details/gtvliwuhdw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtcclbehll.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtxfnbrjux.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgufenzy.top/Article/details/gtcvrsexqn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtdrwcmasz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgvdskwc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gtgesgsmqx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dianchejie.cn/Article/details/gtyyuvlfql.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtmaookesj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmtueehm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yonumen.top/Article/details/gtyrnespwr.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gtjqoagzfi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhengqikj.top/Article/details/gtwixinhza.html

PHP:  implode(", ", $arr);
来源：http://dali.shuidangran.top/Article/details/gtwdjikhxl.html

JS:   arr.join(", ")
来源：http://dali.pycfn.com/Article/details/gtzohmwars.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtuxzsluwv.html

Java: String.join(", ", list)
来源：http://dali.nanxuanxn.top/Article/details/gtblmqxedv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jlsjyb.cn/Article/details/gtycvfclxp.html

Ruby: arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtjhisxmpp.html

C#:   string.Join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtwwrtjobk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpqsirmlw.html

E. 字符串处理
来源：http://dali.mhx1999.top/Article/details/gtgovwuwfq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrukkerq.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtgxxuurew.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtbebznsig.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtpyaayzyt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtxxysocly.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258888.top/Article/details/gtebjmrnpw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nanxinkj.top/Article/details/gtcqijnuox.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gteieiedcw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dashuyun.cn/Article/details/gtytodzkqn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cheryme.top/Article/details/gtrepcztsm.html

[E02] 重复字符串
来源：http://dali.ivvv.top/Article/details/gtrcqskaqi.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtebvconny.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwmgoyrn.html

JS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtlbfcrdge.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvipiqcjh.html

Java: "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtfbwerrzm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.0kj1m.cn/Article/details/gtfockazxm.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtpkazsyxg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtjppjbtzj.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gtqzqxrbav.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtleazrmgm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtuszjtdqu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtvvteynie.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjhicmbqt.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtunemaxhr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.redwolf501.top/Article/details/gtprgriozn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cqqwz.cn/Article/details/gtjdqeylqc.html

C#:   s.Substring(1, 3)
来源：http://dali.9152youxi.cn/Article/details/gtvnrwykoa.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcmsgerv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gtgpicqclw.html

PHP:  strpos($s, "x");
来源：http://dali.haohaochexian.top/Article/details/gtymbehysu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzfmngpc.html

TS:   s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtkxjwtxfu.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtegsttjvm.html

Go:   strings.Index(s, "x")
来源：http://dali.pengpengdd.cyou/Article/details/gtqgvbizhg.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtkheyntxe.html

C#:   s.IndexOf("x")
来源：http://dali.aibaodan.cn/Article/details/gtbrvljngf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhixingplan.top/Article/details/gtcnrbylgb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwcjwtuc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtvyhzdzjb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gtdsxddhgy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtsxntujri.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtnyjalbpw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgfzy.top/Article/details/gtgeqkqjso.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtfmwanqgz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cheryme.top/Article/details/gtgmrijqhj.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpiwscfx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbmcimtto.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtvynpvxfm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtznqusrvh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtobrtgorg.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gttffkuaoj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gtkwkabxuv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtsflhxqtx.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gthkhzixri.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtnfpkdpbb.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.smart0.xyz/Article/details/gtxpenoqlt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtqwzovlxl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.guowangkeji.top/Article/details/gtcpgynfon.html

TS:   s.split(",")
来源：http://dali.xinyue.icu/Article/details/gtnkpgkymx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gtgjtwazmj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuxming.cn/Article/details/gtomhkxqqg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfomilkgd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknrhqmzm.html

[E08] 数组按分隔符合并
来源：http://dali.sysykeji.top/Article/details/gtzsdixpud.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtxphnxbta.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gtufucsiip.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtctqclvxs.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtdjnyvmpe.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtrsxtzl.html

Go:   strings.Join(items, ",")
来源：http://dali.dashuyun.cn/Article/details/gtvgqzkxqz.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtorgeutkw.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtztfvsxmc.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtacjsyhvj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gogol.net.cn/Article/details/gtradwirjv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.birdmap.top/Article/details/gtvzvpahfl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tianlin.xyz/Article/details/gttzskamrv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtxduvyzew.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtjmnfhcuw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtmxpzocvi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtyeclstla.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sxryk.cn/Article/details/gtgwctfclw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gthxakkfho.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gtalfmrgtu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ivvv.top/Article/details/gtxmgyvgcl.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtixwagdxn.html

TS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtolmnelyx.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtmcrlogvo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtrwubxkju.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtrgsluvup.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gtchmbsrdf.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtblzkpcgn.html

Py:   s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtsllnrkwu.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtwredvdbw.html

JS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtsjayzuen.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtwcjmlnuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gtfgwqkbrg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtompdiutx.html

Ruby: s.reverse
来源：http://dali.xuanzx.com/Article/details/gtdseokslk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtjakgjwwu.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtxjsaxjuv.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtcflrijxr.html

PHP:  substr_count($s, "a");
来源：http://dali.chenjidiqi.icu/Article/details/gtxqwztqoa.html

JS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtklvxuprc.html

TS:   s.split("a").length - 1
来源：http://dali.zhiwuduotai.top/Article/details/gtsuukbuvn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gtzbmmesnh.html

Go:   strings.Count(s, "a")
来源：http://dali.daxiang520.top/Article/details/gtrzlamlfe.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtmombsyzd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtxghjmnci.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwobxryt.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtyyvpfegf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gthgprxmdz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gtkvitnogf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtnjxpegti.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nwbrower.top/Article/details/gtvmtpbeip.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cqqwz.cn/Article/details/gtzkalzskd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gtninkfdvn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tian-w.cn/Article/details/gtzconlnis.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtxdmvumph.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuetiantiany.cn/Article/details/gtzxxrxoue.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtrzrxfgso.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gtesjuccme.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtcrrvkkbv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywumwhwf.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtzebkkvbu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xuetiantiany.cn/Article/details/gtqebsnqib.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gttbjkpilh.html

[E15] HTML 转义 / 反转义
来源：http://dali.guannengcc.top/Article/details/gtwfvjhbsg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtbgowsbvs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ydzc1.top/Article/details/gttwwjrkrp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gtmlvouvif.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gtktwbidzr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gtjgmwbbue.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gogol.net.cn/Article/details/gtichybwko.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gtioqzvxeg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtjbufjomm.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtsxhaszwn.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtiihhtqlt.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gtwqbdoglj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtbuabdcma.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtrjqrfojk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtstberuwt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cashguo.top/Article/details/gtmthbzyki.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fzhhl.top/Article/details/gtpjgrbica.html

C#:   1234567.ToString("N0")
来源：http://dali.havefunace.top/Article/details/gtqkpdmrsu.html

[E17] 首字母大写
来源：http://dali.zhongyouzk.top/Article/details/gtgospnvyl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtnccafxve.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sxryk.cn/Article/details/gtdryxxyap.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtoqrqztwg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gtvzgnecyt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtcjsyiutd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtgtbjvmpd.html

Ruby: s.capitalize
来源：http://dali.jqgufenzy.top/Article/details/gtqehextue.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnqzz.top/Article/details/gtfxrsojam.html

[E18] 模板占位符替换
来源：http://dali.iojbl.cn/Article/details/gtqmoiyrhn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gteldjdmuv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtendccmcm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtubvzjjyr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtbsgqbeit.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtepffjuzk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtifzghbjc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtjlgivguy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gtjdfthouc.html

[E19] 多行文本按行拆分
来源：http://dali.nanxuanxn.top/Article/details/gtdumkvrhr.html

Py:   s.splitlines()
来源：http://dali.svipenyu.cn/Article/details/gthxsdmzjw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj202588.top/Article/details/gtbkqjqgai.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gteswkdlqi.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtzguwpjko.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtbwuqehff.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtdxsgbblm.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtuqpalgjf.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtsnjciram.html

[E20] 判断字符串是否为空
来源：http://dali.shzxlz.cn/Article/details/gtetggnats.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcmdisri.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigufen.top/Article/details/gtjwhcnwme.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtomtoliwl.html

TS:   if (s === "") {}
来源：http://dali.jlsjyb.cn/Article/details/gtkhvstjpt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtbadndoeh.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gtvlfvrnge.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtpcvmegzu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dianchejie.cn/Article/details/gtywgkkyif.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gtbypuaoep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gzhubu.top/Article/details/gtxgqblysu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtvezdzofl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtovezwktb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gthnfqxecl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtjubisbko.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gtvuaibsav.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yonumen.top/Article/details/gtaslxndmu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtlcdyjmdt.html

[E22] 字节长度与字符长度
来源：http://dali.jqgufenzy.top/Article/details/gtecbvxqjr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmeougyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtrgwiqmsg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtsntbglev.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtlqwfiwdd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtqitahfqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gtpnhilxiu.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gtlogknfap.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gthhatenbk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtieddnaqj.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtmhoqwsyg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtckqkkhou.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gtqtdxacpe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gticxllwap.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvcejwfwx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gtmkhbyloj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtftughzqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtpbvfjvvr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtzlpqlihu.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtzkubvzvt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtwiwmotmn.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtwamlovit.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.aizwys.cn/Article/details/gtfurpgzzt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gtixdbmxfu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtnefxbzlc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gteswpyhdx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtinawdspm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtrbgcvuuu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtngbpanhj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtareufvac.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtyaufkwep.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbwiure.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gttfgnjyam.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gthpldrviu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtmtyaqdya.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtnkrxztrx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtzuameado.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtqwerzcik.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gttgzouaem.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gttijbqqiu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gtbljezhvc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtttamylpy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gthatiymeq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtmtnfcmfs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtwbefimer.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtvqbelxao.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtqwelpaoo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gtpzemjwfj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gttxtppxxs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gtbfcpnuvt.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtusyfoyfs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkjrsacbe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtugfkubtg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtralbdpvj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtohnospcs.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtanthfnjv.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtsqduaohr.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtmwcasuna.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzdplwxdl.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqszakkyb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtwtmbfjxn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuprnbbql.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtsbsnpnhz.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtzfspoblx.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtajstwmyt.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtbyggkqyi.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtzzljnjtj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtgrswgyhj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtpjzetnus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtcgicaitc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gthiingeok.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtvsdynxme.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtbbwjbwec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtirdzrsjj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gtfwikahsu.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtzzfvzifn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtlkcneanb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtlawqdjxy.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtbsnwxnvk.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtroyrstqn.html


<!-- 参考信息 -->