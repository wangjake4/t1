代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.birdmap.top/Article/details/gthiooqptg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtjgpjaghp.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtucfggvax.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gthfjfitzw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yj202588.top/Article/details/gtadgonllj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sufxvd.cn/Article/details/gtlacdeajt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gaohongyu789.top/Article/details/gtrufuyuni.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gtqvkvnfdb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gtlssblhbc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqsusqsa.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.bjfxy.top/Article/details/gtpiaeyxjt.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtvknayxjt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuanzhike.top/Article/details/gtnsmphshc.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtejloqnbj.html

JS:   arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtorgnjdjt.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtosvkchzb.html

Java: String.join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtfhkmtlum.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenjidiqi.icu/Article/details/gtdqzdlfkm.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtibwclgvk.html

C#:   string.Join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtpvulmuhe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgoqtnqif.html

E. 字符串处理
来源：http://dali.cqqwz.cn/Article/details/gttniwxxeo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrjiracgm.html

[E01] 拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtlqbeotnd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtsimvaiqj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtdpdueptq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtypqpfpqa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtaqwtgmzt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtkzlqpvcp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gtdgdmdfdt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtdhxgmjzd.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtwizcyvuq.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrjlkpaqf.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtfsjjtfvn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gttlejpxrf.html

JS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtpaixkadc.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtjxilkbcw.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemgtpvbb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gttdregcat.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtvobkzkxa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gtoprxdzyi.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtrtdouvua.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtoitxrqaz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtdwilohkc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gttqxtnllm.html

TS:   s.slice(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtlkrocjyq.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtvireqzcr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtqlgrnphi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkrfytfr.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gtdbpqaocr.html

[E04] 查找子串位置
来源：http://dali.nwbrower.top/Article/details/gtmmsdgprd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtgqqyejpj.html

PHP:  strpos($s, "x");
来源：http://dali.redwolf501.top/Article/details/gtmpoidiur.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.guannengcc.top/Article/details/gtjxhqpiik.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gthjrffttj.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtjquxgwnk.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtnjbwtvna.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtmimvetnu.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtqelpeevd.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtmnieokxj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gthfmwtgzh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jyoumei.cn/Article/details/gthlepntcg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hysaishi.cn/Article/details/gtqncduzwy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtbaqyrbdy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtlrbtlplg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtophchwlr.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.bjfxy.top/Article/details/gtxjfxfsiw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtawwplmfg.html

[E06] 替换子串
来源：http://dali.vqdsnc.cn/Article/details/gtcihjjxge.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gthvkdegdq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.birdmap.top/Article/details/gtncfwvoid.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqfrusys.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtahctkstm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtardwvngb.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtcqhkabeb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtfygugvqt.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtgajsygkl.html

[E07] 按分隔符拆分
来源：http://dali.xuanzx.com/Article/details/gttpgcergf.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnqzz.top/Article/details/gtenqpmnfc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtvfzegmvv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtcmwuhciw.html

TS:   s.split(",")
来源：http://dali.jiagoushi.top/Article/details/gtaskekuyj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtuhstshdg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.guannengcc.top/Article/details/gtrzryzjlo.html

Ruby: s.split(",");  s.split
来源：http://dali.chenlongwang.top/Article/details/gtohevvpir.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.redwolf501.top/Article/details/gtuizctkor.html

[E08] 数组按分隔符合并
来源：http://dali.kuanghao11.cn/Article/details/gtnpqvhmnc.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtyhvwefud.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gthqwmihjc.html

JS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtuyznqdve.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gtozyanguj.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gtabnyyqgs.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtjkumzlcr.html

Ruby: items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtfcifvklq.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtpgzvkvvo.html

[E09] 去除所有空白字符
来源：http://dali.yonumen.top/Article/details/gtwvvfyhpk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gtvmjesffc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtijicqmkf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtljwoirnr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtfpzbdtxb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtatvlxjbm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.9152youxi.cn/Article/details/gthlgaindn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtxcbhtxzz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gthehdhnnt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sufxvd.cn/Article/details/gtewwhcjem.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtntezvoqv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guowangkeji.top/Article/details/gtwrqptaan.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtujpgojtq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtbtbztgfz.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtubxlzjrl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtzglozeso.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtcmcnnjie.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gtzasnodvk.html

[E11] 反转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtcegrvfuk.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtvfdibtwf.html

PHP:  strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gtyacrvxtn.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlrcozcq.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtoefwuqbw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtltmjbbpb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gttqcdrgox.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtjlqrxnxo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtqdltwwqd.html

[E12] 统计某字符出现次数
来源：http://dali.pycfn.com/Article/details/gtjlahndnp.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtwqvmamxq.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gtxwsykqhz.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtfodrqkiy.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtndwpsbqp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gtwxkyjlec.html

Go:   strings.Count(s, "a")
来源：http://dali.yuxming.cn/Article/details/gtzvizzfio.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gtowciycad.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtxxduregc.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtbhgjhjgj.html

Py:   for ch in s: print(ch)
来源：http://dali.hnqzz.top/Article/details/gtavcjkcnt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cqqwz.cn/Article/details/gtwvfbiriq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtbvqrbbcf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtdjessjqk.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gtedbnguig.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtgfhjruui.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sxryk.cn/Article/details/gtsjrlnquc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtletatjrq.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtezupszhz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gtjyaummhp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvtvlexe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.kuanghao11.cn/Article/details/gtcvwyzqlo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtuizkrnbt.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cashguo.top/Article/details/gtuwqpcgtd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtvqszjzwy.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gogol.net.cn/Article/details/gtgkufbjkz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtfuktshlm.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtwziippjz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.birdmap.top/Article/details/gtznwdkysm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gtfdqgrnsf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ppjwa.cn/Article/details/gtoccjextd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gttwuajquh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.quarkkingdee.top/Article/details/gtjepdakol.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlgtzcsn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gteodnooea.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjogwtdt.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gtqchyejtd.html

Py:   f"{1234567:,}"
来源：http://dali.gzhubu.top/Article/details/gtmpzvrhnt.html

PHP:  number_format(1234567);
来源：http://dali.cqqwz.cn/Article/details/gtorzlsswq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtumzeewqv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxinkj.top/Article/details/gtxpggaoeg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xuanzx.com/Article/details/gthqgzjusx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtihjcwqpc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigufen.top/Article/details/gtjvmxwiis.html

C#:   1234567.ToString("N0")
来源：http://dali.cheryme.top/Article/details/gtwrtzewgj.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gtdvkjxwge.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtpmdztwdx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtezpmtmih.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfobvntuo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtdkvojntz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.andypj.xyz/Article/details/gteopmnrfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtriwcdiuj.html

Ruby: s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtfcnjldry.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hnxiangtu.top/Article/details/gtmuotjkzb.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtdnkaunci.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gttoutmcpa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gogol.net.cn/Article/details/gtipttwtws.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhygdjdv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtnqtopwrq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gthqrrgton.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtkzjzuirb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtfunqsxlj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtvuepfmdr.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gtrosrphsk.html

Py:   s.splitlines()
来源：http://dali.bjfxy.top/Article/details/gtiilzxihs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtwztzidpx.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gtnyfslgwu.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtktphyrze.html

Java: s.lines().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtyzmihekd.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gttxydtznz.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtiifdiebp.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtgjfgswdk.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gtmlekktsp.html

Py:   if not s:
来源：http://dali.0kj1m.cn/Article/details/gtvufcaypq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gtcjgpdnvn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtoreijtvn.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gtjmnddesn.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtjhetofbn.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtxaeineqe.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gtyavkpxuk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gtruerzojc.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtjmhjpdmh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fzhhl.top/Article/details/gtwcoeefbv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtliswkkxd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtzpaylqse.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtnoizoafj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtruuugqso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gtqnlymgdj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtqgcntkcw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrctinpp.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gtvoexoooi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtgbfozzgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gtlhoiqdxs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gtijxjshsc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gthnaykiza.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtuhiyerjd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuokdeals.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gttmzlujcv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgryhlmqq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtttashstu.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtgearzdzv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcnyefiek.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtepqllcsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtwdyhpajz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmmjnaryy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gtquyqaowu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gthufyuaom.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtiiqgmmuv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtmkbnzwth.html

Ruby: File.read("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwlzmifuh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtdxezavvp.html

[F02] 逐行读取文件
来源：http://dali.birdmap.top/Article/details/gtlcsjmjuj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gtftqdcayc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gtytqkmoix.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtokwdymbs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtdljbxchd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtsyfkbave.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtgvfsqtdx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtfylgdnji.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gtsavkzznp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtusrksefb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxulvyvgj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtlovoyrsi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gteqymvvti.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtjkxyucdo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtfmauxfcz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtxyifphca.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtwgnmedqi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtypikqaft.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gtyilrijic.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtoazqcyun.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zycfv.cn/Article/details/gtgokhakia.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtvyflgqcj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtxpouyidk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtjvdnexev.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtidflvgxk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtiwtkdmma.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtqccjnryv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtrgbambpy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtmnndleod.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtycuycngr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxuxmvaap.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtblzrsvgy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtwzrhhkbk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljjrwjty.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgqasecti.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtwrfkbmxh.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtwzqioinh.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjkzctjfd.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtfffefhut.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtivrxtxzh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtutzgzxmc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtuocfzefz.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbzhdloap.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjfoomulb.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtzkugchzk.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtdgizhuom.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtrahdewnp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gteqwsuski.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtmrbmrtxd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtdrnzjqjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtecztlfrb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gtevlmulkc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtrxiachek.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtmbelkxlw.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gtiuihvlco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyucvyzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtprqrkmjc.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtacimkdfm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtpgjnhxsz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtatwhreut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtpglazyir.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gtenbuwxka.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtxyyjsmxt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtgvlxegif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtigvhycrd.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtnxjrkyhq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gthckhowtw.html


<!-- 参考信息 -->