代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gthxgepimo.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtrszbxbuu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.bjfxy.top/Article/details/gtbqkluhhf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ehwqpu.com/Article/details/gthrfpazla.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwscfkkhz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtzypjhsor.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gttyiwlgyd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtbjibdvby.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtunyrcsrf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gtvxradsvn.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gtqkohlvbl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtppaaytvf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtjtdmuelx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gttkcamqqf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.feifeiyinyue.top/Article/details/gtnovvxemc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrhxctrcf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtvcfspehj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zycfv.cn/Article/details/gtdfplryxk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtxwpcwjxk.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtulpbadcm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tanke756.top/Article/details/gtnkqkbtac.html

PHP:  implode(", ", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtsiutrvyp.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gtkcwavwlv.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtlfvwjnop.html

Java: String.join(", ", list)
来源：http://dali.mhx1999.top/Article/details/gtktjtuqcy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gtogbqktvd.html

Ruby: arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gtiznqzppc.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtupkpiptc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgxcurqlw.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxguojmih.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdndwcqwp.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtqazfebqf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvohoqza.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtlhwtytiv.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sweek.top/Article/details/gtxfyaiinb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtvvdqcbdu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtknuskren.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtibfbdlgw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gttrejwebq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtgqiaczip.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gtkzdoqtwn.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gteioiriro.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cucudq.cn/Article/details/gtwmkudbho.html

JS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gthoyxdaec.html

TS:   "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gteqsbijtn.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifyffjjw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gtcnomdihb.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtupdcidim.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.svipenyu.cn/Article/details/gtrhgvfhtt.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqmulgwb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtucxjyvwn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtuxvunwdw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtncqyhjvw.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gtcnxbfrxf.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtjzcbosgg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.havefunace.top/Article/details/gtmmtrriwn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtbohmnjbk.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtcvlgqaqk.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtietlzmfb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtzoiupybc.html

PHP:  strpos($s, "x");
来源：http://dali.jinqigufen.top/Article/details/gtpizccuka.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.smart0.xyz/Article/details/gtjeorlxfc.html

TS:   s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtlokkymtt.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gttdifievc.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxqnvsvj.html

Ruby: s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtlyochina.html

C#:   s.IndexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtczptjmlp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtcvgdcmjo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtcckarmgk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtcpzadizr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gteiwixrxe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtdsfxoxrc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtdwnxdibo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieruynfo.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtounvumrv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtjauouuql.html

[E06] 替换子串
来源：http://dali.sufxvd.cn/Article/details/gtkndibqco.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtgogstdxz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gtknhuzusv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtjyphlhjv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtkmjcnvhq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gthtuyluth.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cdnleiting.top/Article/details/gtkjhwydlu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtahyiujsb.html

C#:   s.Replace("a", "b")
来源：http://dali.yj202588.top/Article/details/gtudadcubd.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gtjkboxfbx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gtxolbwyct.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtyvgkcoeh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gtklrjgfwo.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gtffkaxexo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.feifeiyinyue.top/Article/details/gtrreucagl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtrpsankoi.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gtnwmzfgzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gtuudufhqf.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gtdyoqqzpq.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gteosaiily.html

PHP:  implode(",", $items);
来源：http://dali.gogol.net.cn/Article/details/gtfwhdilpv.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtvtpipmyy.html

TS:   items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtlksfvtsq.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtfvgwolii.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtrmwaavoe.html

Ruby: items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtuvkcqvnx.html

C#:   string.Join(",", items)
来源：http://dali.cashguo.top/Article/details/gtkgsobilk.html

[E09] 去除所有空白字符
来源：http://dali.jinqigfzy.top/Article/details/gtsqmncsoh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnqzz.top/Article/details/gtxhoehgdj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtbglxrefo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgufenzy.top/Article/details/gthuzkqdto.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gtnhrlbnaf.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtnqjuesip.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtcnxzxxtm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtrtyfutov.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gogol.net.cn/Article/details/gtmitahlrq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtodbpvyok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gthrdsvhue.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtbqovbfqu.html

JS:   "7".padStart(3, "0")
来源：http://dali.jianghu66.top/Article/details/gtxbdaakul.html

TS:   "7".padStart(3, "0")
来源：http://dali.sxryk.cn/Article/details/gtydgxpnos.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtytqbpcto.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gthtqfnvtv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gthmswdhmd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.feifeiyinyue.top/Article/details/gttbrzbhfi.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyyntzyj.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttidhwxcz.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gthpaedbip.html

JS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtpjydbnhp.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtubuciber.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yonumen.top/Article/details/gtdegmrjze.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gtrhvjmplh.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtyfmrwzju.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtpgygaveh.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtmzcpnjfw.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtejlepvfm.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtdjjjiuum.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gtmtyczhhg.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtqhtnjgoq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gtejyezamp.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkspjhudj.html

Ruby: s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtfpfivcpi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtfoxcoccp.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtfaaxxwkf.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtiumkgogb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gtjilvvuyh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yueranfly.top/Article/details/gtjfyzeflz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtcdkrpxkb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtqwvyreij.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daxiang520.top/Article/details/gtdisegywa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtgeondqcz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhkphpqd.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtumttopuw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenzaomai.com/Article/details/gtjdmihqgn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtdartdhfk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtqidcpzgf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtnxqspwpl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtoltupmzx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yvedp.cn/Article/details/gtzringuqz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtocasjzra.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtwrtgkhki.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj20258.top/Article/details/gtckcbacng.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gtrboqeojr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekcowrtp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwnczpfp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtjcitvkod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shuidangran.top/Article/details/gtewqesojy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtvumvrrja.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangdashe.top/Article/details/gtpekkzwqf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtecpwfdau.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gtldpjnjyi.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigufen.top/Article/details/gtgmmxpxbi.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcokuatoa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtqznmcfry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guannengcc.top/Article/details/gthtmbnuku.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gthuirywrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtmlznurlf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtxcpfxcti.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gtnryzxyto.html

[E17] 首字母大写
来源：http://dali.zhixingplan.top/Article/details/gthlytyyfl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtoqkblizo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gthrpwxaan.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtbxsrvbzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtkqsspfpt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gtupvsbwlq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtoufrhrpj.html

Ruby: s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gthojkuljy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gtenoozgia.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gtjuwcmvds.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.mhx1999.top/Article/details/gtamnbmieq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtmrdhltzo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gttltzbwyn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtqkaqsdiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gthkurjmev.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtkxihpnid.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hywenlv.cn/Article/details/gtmrsoxuot.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtimoymefy.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtwzdrdeej.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtnbwmmhog.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtnrhseixx.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtmgylslwo.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtrtjwqfkj.html

Java: s.lines().toList()
来源：http://dali.yvedp.cn/Article/details/gtzpizwtxo.html

Go:   strings.Split(s, "\n")
来源：http://dali.jianghu66.top/Article/details/gtacrynnob.html

Ruby: s.lines
来源：http://dali.ppjwa.cn/Article/details/gtqjeabjuv.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtfuollwnz.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtavqtbgcd.html

Py:   if not s:
来源：http://dali.nanxinkj.top/Article/details/gtokldgquo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtxcetqfnu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gthrloogze.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtlvfqaqaf.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwytqleyb.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gtrsfhfcpb.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtffoscljo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtewmvkfyb.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gttbeovrvc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtyptxeuvt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwknaloia.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtjvxvxbzz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtirdtkncp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtvokgifab.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtzyounekn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtsemmrmou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtwkyevrbm.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtuiraypxk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtziacixrt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtyehlnzeg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtroxnnyho.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtldearhhs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlubqblbb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gtgnhiwwwv.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gtzrlzqmvt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtmnhiso.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsrmjebvj.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtqvxfabov.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnraeily.html

[F01] 读取整个文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdvlpvpni.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gtqheftbph.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pycfn.com/Article/details/gtddwishnt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.c1oappe.top/Article/details/gtblhnygen.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtccoovikw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtifiepvfn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtjoljychx.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtammacsvi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gtjfvspyjc.html

[F02] 逐行读取文件
来源：http://dali.hfpthk.cn/Article/details/gtdbugpmda.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gtqotayjpe.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtarezvzqz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtdpvvwyyi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtpicygrsn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtijvrvyoz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cqqwz.cn/Article/details/gtyamisvrt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtzdnxvfix.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtaawrezoh.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtnssbsavs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gtaxdjbvmu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtvqmauztq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtnywghxvl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtduwtpakb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtcngpwftb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtttsafzyw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cheryme.top/Article/details/gtefzmvboe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtraatpyjb.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtvntdxfcj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtumwckfxt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gtfoaeqjix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtrrgixcjp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtedtvimeu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtljtijehj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtriujwxam.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gtrmjlcmbx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtltkfixgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtcncngmul.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtckqhoxpw.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtrvdexosb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtenvdqcrl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxtrfbhkm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gttzdkneww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtbddiilei.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcdxfstca.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqoyoioq.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gthkmrhamb.html

Py:   os.remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsjmvmazy.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtltwkrrys.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpszpfhmo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyxhqkfge.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtrkvcbqlf.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gtlyyforts.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkpsypbmz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gttbndlcby.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoumumxeb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtmyharufa.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtsawidkxg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtopriwpxl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnjnyuvr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gteacjemtg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtrgqjmlcv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtmxikcric.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gtngpolpiw.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkmwdsem.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtlkerssqn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtzkxzsojo.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gthoiqalhr.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtlkpcenxy.html


<!-- 参考信息 -->