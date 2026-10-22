代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.birdmap.top/Article/details/gtpiriodjv.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgfzy.top/Article/details/gtpycwhfmf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangshuangyany.cn/Article/details/gtpmqgfpvs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gttpsdmjus.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cqqwz.cn/Article/details/gtzwzcwqsm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtgmurgayu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yangfankeji.com/Article/details/gtnbijmrfi.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gtgwmzcfhb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gthswrapdo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtqpcaibnb.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtafwlwhvq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gtlxzicvpx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtwwfnegom.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtcrknefgk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.kuanghao11.cn/Article/details/gtsiuwtnpy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yonumen.top/Article/details/gtwgvyvahz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cqqwz.cn/Article/details/gtgjlfnayw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtwozygwhn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sufxvd.cn/Article/details/gtqebyalnk.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtlxtuwlpn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jiagoushi.top/Article/details/gtndymbhzk.html

PHP:  implode(", ", $arr);
来源：http://dali.c1oappe.top/Article/details/gtynpdvjte.html

JS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtfjbbpwpc.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gteckottib.html

Java: String.join(", ", list)
来源：http://dali.zhongyouzk.top/Article/details/gtmzljkkxl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtjqatbrtq.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqpjkvsl.html

C#:   string.Join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvxmcosp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjhicngoh.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtvglbslby.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtippvncar.html

[E01] 拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtvsevbiwb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gthsuvcadt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtrmozmcwf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtkpznvouy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgfzy.top/Article/details/gttkfrfjwg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtwrmlpogq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtjlwgzzub.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.havefunace.top/Article/details/gtjqbtfvqr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtjqrxinzp.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtlarrdswh.html

Py:   "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtngayjjma.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gtqystqvtc.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtqzqbctdk.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtyitkgish.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtkcsitkwo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.c1oappe.top/Article/details/gtcwofpcfo.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtwcnvwyla.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.aizwys.cn/Article/details/gtdvtvcxqt.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtrcxdfssc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdewyusb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gthtuxovht.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtdgrzegea.html

TS:   s.slice(1, 4)
来源：http://dali.cheryme.top/Article/details/gtzfkwqpjl.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelrvcpyq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtmawrlvjy.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtqawwycqh.html

C#:   s.Substring(1, 3)
来源：http://dali.gogol.net.cn/Article/details/gttcvfiuyy.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gtzifgbyzi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtutbdnmhe.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtmfljreyf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtpqxtwmeg.html

TS:   s.indexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtkpjlqyrm.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtcguxrhwi.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gtpvqpifpn.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtouodseve.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtbsltvtnz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtpfuzjuwe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtipjmsobt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.haohaochexian.top/Article/details/gtylkzkfcm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtihtxjhoi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtqptzwvgj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtqkcchlys.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtponeifkl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daria6918.cn/Article/details/gtrujripxa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtzpbykprx.html

[E06] 替换子串
来源：http://dali.daria6918.cn/Article/details/gthohxmqrr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtyffobauu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gttyhznbiz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtendzewax.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtbtuyxmyj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtlxcrrngg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtsumfejhq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjbjkcdx.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtnxvadhxt.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtfdgguooo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhijiandao.cn/Article/details/gtgxgtqolx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gzhubu.top/Article/details/gtvumifrsm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jiagoushi.top/Article/details/gtqcqenkyp.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtyqtxndve.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gtgausbngq.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvbpacbpy.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gtursdqmfl.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hywenlv.cn/Article/details/gtjlkymytp.html

[E08] 数组按分隔符合并
来源：http://dali.fzhhl.top/Article/details/gtroprdonq.html

Py:   ",".join(items)
来源：http://dali.guannengcc.top/Article/details/gtpvbejqac.html

PHP:  implode(",", $items);
来源：http://dali.daxiang520.top/Article/details/gtbpfpqhbz.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtvwsqlxdz.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gtkhobcmno.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtzwuahrlu.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtayalhdbr.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtqkughnsi.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtdutcek.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtfrkdyjgc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtobyonjjt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmfngaj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtqcgkgxnl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sxryk.cn/Article/details/gtjhyiqrfx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtjjpittoo.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shzxlz.cn/Article/details/gtomdvmguw.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gthqqkepwh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtwuyxehwc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gtfvlanxvn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtubskrcbg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yuanzhike.top/Article/details/gtsscliytt.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtbkoecxtm.html

TS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gticlyzuwf.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gttxhznoli.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtnpohyphh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtqdszlmim.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hammf.cn/Article/details/gtquowutxl.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gtvzrnjsat.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gteczmaeqw.html

PHP:  strrev($s);
来源：http://dali.yj20258.top/Article/details/gtjoycigqd.html

JS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtjhjjfzlu.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtuhsxnbvy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtzyzsglda.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtcrrsbfxq.html

Ruby: s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gteivlvzsu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtkauqcmsr.html

[E12] 统计某字符出现次数
来源：http://dali.gogol.net.cn/Article/details/gtmbzkbgiu.html

Py:   s.count("a")
来源：http://dali.yvedp.cn/Article/details/gtiurhrzxg.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtieyxzhwa.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gtwvgnbxli.html

TS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtovpiwpvs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gthoamghmu.html

Go:   strings.Count(s, "a")
来源：http://dali.xuanzx.com/Article/details/gtsiyxzbdi.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gtcoftzlab.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyytzkuot.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtiugkskow.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gtwtbpkvvg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtqkzkvakr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gtzkszjzhd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtyenmxzdt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hfpthk.cn/Article/details/gtcaebvijt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtoycylucr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dianchejie.cn/Article/details/gtnasraepp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gthlxiezbg.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtqkxzdkoj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtmkeivwli.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtoaiepnhe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.andypj.xyz/Article/details/gthhnxejud.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtcryivjvd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtwxnkevfg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daxiang520.top/Article/details/gthzfmvgoz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbzjjqzh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtuakrbzkr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtcepzpbkf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtqikxngqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtpcrofysv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgfzy.top/Article/details/gttaeaitte.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gaohongyu789.top/Article/details/gtsihkjidt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zdqjudy.top/Article/details/gtrvtypion.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtvcqflube.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gtquehbcnz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gttougmouy.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gtxhwrudqb.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtnvvvptmb.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gtexboaxav.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtggnressr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gtiqulyosd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cheryme.top/Article/details/gtiionmunw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gtqnfxqntv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtwvkusvns.html

C#:   1234567.ToString("N0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtffkzzumj.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gticlizthk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.aizwys.cn/Article/details/gtseltfepm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gtfvhebwzs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtbycoqrhz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jlsjyb.cn/Article/details/gtydiyhpex.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtxmgsgkiz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cqqwz.cn/Article/details/gtskoxfeze.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtauhvcjbh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtmtbkglqn.html

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtabkpqyyd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.smart0.xyz/Article/details/gtgtxfigve.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dianchejie.cn/Article/details/gtaungazrc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtkkaqdkis.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtprtvvnva.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtudkoqjux.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gtowuisbak.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtosgfqhbo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtflgnbodw.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gtuqiwzaam.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtsurhzxtx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtrgslwsgu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtrocyifnf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtvizmfdmp.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtzjwkhiqe.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gtniolnech.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtwbrvpbky.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtqsznlujz.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gtjnzqzsvz.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiocnevkv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhoulong.xyz/Article/details/gtjxpmzqrl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gtbnuvbxji.html

TS:   if (s === "") {}
来源：http://dali.xziqi.cn/Article/details/gtpaesxvtd.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtemvhlfgh.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gthyhraakn.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtylawbyov.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtaqsdbpzf.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtwhwvtqyw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtdtqgjnyl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtfvcpqltd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtmyverjdd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtdpfeurvm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtyqlaatxj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtlguyjogk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtrgovluay.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtwduqveam.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtfvsfgcvx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gtnqxbrjvq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtcsovsamv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtdefwmqdc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtsddrwbtg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtjgtnqchb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtwevbczor.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtpycsqeso.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrdvnpgi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvldusugt.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwdearqs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdilvacnf.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmcspwrcx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtiknfxmxy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtktvmvnkm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtfnpgojax.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtjcgrmnzm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtgnukqrhi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtptuvycsb.html

Ruby: File.read("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttkwmqmek.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtjlcubhao.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtsrjophto.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gtzpukhvnm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtbatbciin.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtppbcayaz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxaorkwxc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtntynaqsq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gtotvagvka.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtgsjcloro.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gttqwdjzuf.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gtxvuhytsk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtwlierlkb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtnvpkavyp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtxyqskxhb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtbozvguys.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtscmuwsna.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtuygadeab.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtdljrmkxs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtgtfsvfav.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtfsxejuxg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtrwfzhrdo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtbvokxlup.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtjyomzqow.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtibgoywaj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sweek.top/Article/details/gtcevgjrul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtkdwtguug.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtmlgzonue.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtfsafiuac.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtdptujrcx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.mhx1999.top/Article/details/gtkuckukmf.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtzzvpvcac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqxytjnnu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtgshlcxkx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfsncbmy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtoebavrvc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtwmkxmrir.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtuawkjdwh.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlgsmjyvg.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtnefmmzgt.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtwyhgbaqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtodybyazr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtvhqeyxny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtqjkiadmj.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthvdrpqqz.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtanzcfjcm.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gthkwpvboj.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtihtwvfar.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtelokftmy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtarumtted.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtkinisabe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtnmjwdqwn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gtpyhqnwod.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtcxfiggna.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtnaqmpjct.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtpqqicrfe.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtjqvpfwcr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gttlqwmjdt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtbevakkyu.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtdogzbelo.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtbzzqepon.html


<!-- 参考信息 -->