代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cashguo.top/Article/details/gtqprmrilo.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtypteeffr.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gtbyuuiekn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtrjocplnk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgdwffwi.html

[D24] 字典 / Map 基本操作
来源：http://dali.yuanzhike.top/Article/details/gtthevyrtg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtkujalfjw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gtntxxautr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gtofczkxfq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtvbvjivyy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daxiang520.top/Article/details/gtyvdqculm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gtcyemlqtw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenlongwang.top/Article/details/gtiunvzazm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtjelxadri.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gttcnolxtm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258.top/Article/details/gtgdtforbv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtkddssoxy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtneknox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gzhubu.top/Article/details/gtifyhviwp.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtoxihtzqm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtsxvmggcv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gtuftzocrn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtflcicosj.html

[D26] 数组转字符串
来源：http://dali.svipenyu.cn/Article/details/gtexwpicbu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtskrwgtpa.html

PHP:  implode(", ", $arr);
来源：http://dali.mhx1999.top/Article/details/gtqyswxcwb.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gticqectsx.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtmxnjdnvq.html

Java: String.join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtbuiloaxy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shzxlz.cn/Article/details/gtblxrshyb.html

Ruby: arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gthvglixbq.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtuotamybu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnndubjcd.html

E. 字符串处理
来源：http://dali.zhoulong.xyz/Article/details/gtwkcmhekm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrhradqur.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtllhwhtsj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daria6918.cn/Article/details/gtkqyzmfto.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtjmybgwbb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtnvvbulzt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtzndfcgvp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daria6918.cn/Article/details/gtrwkouqlr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gthkvkieef.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtoqbitgnc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtnsvxxbue.html

[E02] 重复字符串
来源：http://dali.zhiwuduotai.top/Article/details/gthjdvrubm.html

Py:   "ab" * 3
来源：http://dali.mhx1999.top/Article/details/gtmobygvwx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gtxkwytgbl.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtzhiyoldi.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtszwrxkyg.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtadptuiqq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtpsmclmyn.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gtmrbkkzca.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.mhx1999.top/Article/details/gtmsocaxgq.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtqdkwijyj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gtkwvnjyhh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqyltgyv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtzmtqjjfc.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtydjedovn.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtpxexlgaa.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtmtojcthq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gtlywjdzhf.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkwbgqny.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtlbdvpbfc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtchradttn.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafvcuvic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtwdqricbs.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtlceimmgh.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtmnjnlxsk.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtzsldxqrp.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtujcgsexp.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gtjxssuuyj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtxkxzdwgd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dianchejie.cn/Article/details/gtbzjnikqz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gtfkyorgni.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtjaywhoxy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gtnbcadswt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gtrduovycj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhixingplan.top/Article/details/gtcbxqlntm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigufen.top/Article/details/gtmezyohio.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtloxlqmvp.html

[E06] 替换子串
来源：http://dali.jianghu66.top/Article/details/gtjgpgzjfn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtgeurhoxn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hysaishi.cn/Article/details/gtiaenpomq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtqfwmzuxj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtdbhoqnou.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtsyvpbtko.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtgxwqgzqh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtdymiewwc.html

C#:   s.Replace("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtxducbugf.html

[E07] 按分隔符拆分
来源：http://dali.dianchejie.cn/Article/details/gtawbpxiyo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtimmvzwbd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtnadsegje.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gogol.net.cn/Article/details/gtoadhheyy.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gtnlrcoevv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hfpthk.cn/Article/details/gtmtviafwf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtciuiapeh.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gtexanoyre.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xziqi.cn/Article/details/gtyscvsogi.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtvqfzowry.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtsxhwhgtx.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtlktfkldt.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtqvukkbdc.html

TS:   items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gthsstclxb.html

Java: String.join(",", items)
来源：http://dali.yongpay.top/Article/details/gtdjfdlzpd.html

Go:   strings.Join(items, ",")
来源：http://dali.hywenlv.cn/Article/details/gtlurhvztf.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnlmymtk.html

C#:   string.Join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtnsmvovop.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtlcqtgwlj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoohohzm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xziqi.cn/Article/details/gtjozhyzci.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtulgqszvx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtjbledfgb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtjoevauqb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.meibo888.top/Article/details/gtsecbncmy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtbqrxlowg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtpvemnclv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtselwrbou.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtrzgabrth.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.meibo888.top/Article/details/gtvfhlffvy.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtlhvuvszg.html

TS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gtauawcenx.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtjasciqgu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtqoypqcwx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gteqceqeui.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.snrcjt.cn/Article/details/gtyvlckunr.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gttpcbhnfz.html

Py:   s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtnciihemx.html

PHP:  strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtydqhgjth.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtjmtdxssg.html

TS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtogzntbpe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.c1oappe.top/Article/details/gtfpcpuoev.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sweek.top/Article/details/gtaryjiwnb.html

Ruby: s.reverse
来源：http://dali.zycfv.cn/Article/details/gtjbjrebqm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtknxbfpqg.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpovknaf.html

Py:   s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gtaeeyeuwd.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gttwzohgvw.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gtlnuhpccl.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gtrpnmbati.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shuidangran.top/Article/details/gtopxxdcpd.html

Go:   strings.Count(s, "a")
来源：http://dali.chenjidiqi.icu/Article/details/gteaoyabgp.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtjiwtbwjf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.pycfn.com/Article/details/gtfcbnerjl.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gtlefvlwrn.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtxnogcapm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gtmvrpsrkz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtrgigltjj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gtburzjxuu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtilonoeeq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gtjxmirzod.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtjhoowczo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gttwisqpwa.html

[E14] URL 编码与 Base64
来源：http://dali.jianghu66.top/Article/details/gtntxttwha.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.haohaochexian.top/Article/details/gtgaztyuya.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xylfe.cn/Article/details/gttodbfugm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtjdjrvokb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gtourscwob.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gtedyzckfv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gtkhexnwit.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gzhubu.top/Article/details/gtshoystxv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtendhfdch.html

[E15] HTML 转义 / 反转义
来源：http://dali.9152youxi.cn/Article/details/gtkmihxiac.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtvocsrala.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtxuzkhtdx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ivvv.top/Article/details/gtpdbixekc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtkxyuxxdc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.wangdashe.top/Article/details/gtqvsuggen.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.bjfxy.top/Article/details/gtynlmpjfs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtxxnorzkf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtupuqezmx.html

[E16] 数字千分位
来源：http://dali.fengsongda.top/Article/details/gtdrfqthyw.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtrubogxrc.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gtpxiboigs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ybcxt.top/Article/details/gtnaeyktem.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtcasicgwz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.birdmap.top/Article/details/gtvwdisllo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.birdmap.top/Article/details/gtgmhzxnot.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtbegwagsf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtikaoyvcu.html

[E17] 首字母大写
来源：http://dali.fengsongda.top/Article/details/gteajjjury.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtxxmethvc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gttxhwmehn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoacroeo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gtndscovtd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tianlin.xyz/Article/details/gtlgbqajfu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gtjwllsxqn.html

Ruby: s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtmucvaffn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.vqdsnc.cn/Article/details/gtmtfsmxfe.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtjqwviari.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtngndeziq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cucudq.cn/Article/details/gtlcgnxsjq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtalvfpawu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtzovkdxnb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtxioywynj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtprxqeqjc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtknvtdcir.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yanxiufei.cn/Article/details/gtcmltiaif.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gtsbhrojdx.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtohkaojvr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnqzz.top/Article/details/gthefxocyt.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtzpfsplrn.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gtcqntumlc.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtmscdsyie.html

Go:   strings.Split(s, "\n")
来源：http://dali.meibo888.top/Article/details/gtbiqkezbu.html

Ruby: s.lines
来源：http://dali.haohaochexian.top/Article/details/gtwajolibt.html

C#:   s.Split('\n')
来源：http://dali.sysykeji.top/Article/details/gtefojbtvp.html

[E20] 判断字符串是否为空
来源：http://dali.fengsongda.top/Article/details/gtkelcjeih.html

Py:   if not s:
来源：http://dali.kuanghao11.cn/Article/details/gtqacjicuh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkyebsmm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkenxizpz.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtzhsawwmp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gttmuhodjv.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gtwyrhpcll.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtdleikvzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gtivvbwdpf.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gthcugsnor.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtsfubjgof.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtynvpoomr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtuxbajafi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtsnegnkow.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtvjwsvujs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gtanicnrgq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtjqevdrcq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtxmcymmml.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtufjuakhc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gtcfxbyzlr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtmastqhyv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtxuglbmff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtcgknnmyb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtfefivlsy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hfpthk.cn/Article/details/gtcozxdpqq.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtmrjfzvar.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gtyrtxouzf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbtrnspjo.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gttbaqfqxi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtavqzzmoj.html

[F01] 读取整个文件
来源：http://dali.iojbl.cn/Article/details/gtmtvasrtk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtbalvvwnm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtwuawcmju.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtaqbkuzik.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtyedjlqhy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtzfeuzylm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtyfkgulsh.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtkidrvysz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtrmrbmlbm.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gtkjkpnjbk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtqobrdwql.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtttflvdmy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtlkrjapbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtnajbpoow.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkohsswjw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtaaaqxcix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gttomooqsd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gthvfzavpe.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtadehnmzv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gtwnfvspab.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtiwfsjdhx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtkiflnkpk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtkltmhuvq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtlkvxleco.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtkpdqnoco.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtssuwtbjm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtfwrojwdh.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtmixbxiol.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtnorcdtuj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtkrchzkql.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtwszckkzj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtvdnplona.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtysvmtxxx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtaffpaxss.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gtnqxdhudm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtupqosnpi.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gthscvyveg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtyrllujrg.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtgsjgyvbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtokstrghw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlieohyvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtfmqdulwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gttsywtnfo.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtzxdswukm.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdonxwafp.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjgsbkmn.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtxjfdycuf.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtylouepas.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxvnlpnru.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkdiivpqd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtgplcqgxz.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqbgecelk.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfprpujin.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtjlvxcjrx.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gttasrwzrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtufulqwex.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gtydrbfhqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gterdrtnpf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiolvnlyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gttvelnmko.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtxpylxcmm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtidjzotlf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtmlnwtmpx.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtabijhdfo.html


<!-- 参考信息 -->