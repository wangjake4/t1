代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gtzkdeqkbp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gthqotnvez.html

[D25] Set 集合去重与交并差
来源：http://dali.guannengcc.top/Article/details/gtrawkglai.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtnpqifbzg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtafaatwjk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenzaomai.com/Article/details/gtrofxjwxm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtdjvacxak.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangdashe.top/Article/details/gthwxqucgr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gaohongyu789.top/Article/details/gtwinjeocv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtoxobervd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtcgrjvtye.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtufcdbamy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtixrcussk.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtxeenvdau.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtxcntkptf.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtsjjnvyqy.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtbefjfqpc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtckqgtfjx.html

Ruby: arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gturyvgfxs.html

C#:   string.Join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gtgxsolzwu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjdynkbvg.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gtowfxplpv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjhjykvur.html

[E01] 拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtlgxbwhnm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shangyingyoupin.top/Article/details/gtmejwsast.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxuanxn.top/Article/details/gthvuoqfgf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtwihaqoxe.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtitgfvkxp.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtrvmnojnv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtycrwwtxh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hysaishi.cn/Article/details/gtxpbqovnk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gthomzrefk.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtqpyuyecp.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtwtsecybw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmmpintw.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtqotweokr.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtjyeojghc.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtjrajkrdv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhongyouzk.top/Article/details/gtmsqgpttg.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtqkdurgen.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gteplpvqcl.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtufqxhcpm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.chenzaomai.com/Article/details/gtoywiwrvx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtcomfpajr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtfscvbpol.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtiryuzatx.html

Java: s.substring(1, 4)
来源：http://dali.tianlin.xyz/Article/details/gtycygrpsc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gticxbtamr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtrsmsignb.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtsjlbpaqd.html

[E04] 查找子串位置
来源：http://dali.dashuyun.cn/Article/details/gtfotxxjwu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gtxqthptjk.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gttmaokcsr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuanzx.com/Article/details/gtehjtdufk.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtjtumzhpo.html

Java: s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtceochplv.html

Go:   strings.Index(s, "x")
来源：http://dali.yvedp.cn/Article/details/gtwtddsdif.html

Ruby: s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtfdyqtyxc.html

C#:   s.IndexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtpxypyyqj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtsckvhkqs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtpffemjfm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxirnahwo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtwwfnjotx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gtajwrqdbg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtiqbtiari.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtxtbdrgne.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gtwvlxsyay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tanke756.top/Article/details/gtjzvxirfj.html

[E06] 替换子串
来源：http://dali.yongpay.top/Article/details/gtfygdboot.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gtmkelmkbq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xinyue.icu/Article/details/gtlylchazk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtnymjdume.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtyynicuss.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtbwmiyccu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtmfkobqeo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtssnmnjgs.html

C#:   s.Replace("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtqmanojjw.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gtexfdjmyn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenzaomai.com/Article/details/gtyobyilnc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtwkyhoeos.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtirvltjrr.html

TS:   s.split(",")
来源：http://dali.yangfankeji.com/Article/details/gtolambbwo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.dianchejie.cn/Article/details/gtpsbchods.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtsdgwcolw.html

Ruby: s.split(",");  s.split
来源：http://dali.fengsongda.top/Article/details/gtnbctlrgx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gtpeccyiaf.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gtxlaoedzi.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gtkgydvpud.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtqfzimtos.html

JS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtmpskggru.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrxtkufp.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtleqfmyvj.html

Go:   strings.Join(items, ",")
来源：http://dali.haohaochexian.top/Article/details/gtakrsixlj.html

Ruby: items.join(",")
来源：http://dali.meibo888.top/Article/details/gtlquyfvul.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtqqunivon.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gtckgjohhj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigfzy.top/Article/details/gtnckagspx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspicuwey.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtxlvggwge.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtnvsobrfl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtbtfujdtv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtbvdevfaq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxiwbtsb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmokzqcuy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.aibaodan.cn/Article/details/gtnveglteq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtaftnkzvc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtlgfdenut.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtehqkthbf.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtuitvnqhz.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecccbzjc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtblwhsbmu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtnqcumvhj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtavvrnttd.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnleasnfx.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gttydoxyzh.html

PHP:  strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtqaomtkrs.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtrsowrlgy.html

TS:   [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtkyikdgno.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqslxtnh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtteiekzkw.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtednmuyqj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gttwpnjlwa.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmovxjpd.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtnbronjlc.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtetucbmbg.html

JS:   s.split("a").length - 1
来源：http://dali.hnqzz.top/Article/details/gtwbajqqym.html

TS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtykkocono.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltlfqfog.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtdrdkfukh.html

Ruby: s.count("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtzasicjfp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqopldxg.html

[E13] 逐字符遍历
来源：http://dali.yuxming.cn/Article/details/gtxkxzlcnc.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtjzutiirr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtjugfefej.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtjzqlsqxx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtsjghvzlj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj202588.top/Article/details/gtnzmvmlxg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtnyjyfpzd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gtnlfmqwie.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtlllzrpty.html

[E14] URL 编码与 Base64
来源：http://dali.316326.xyz/Article/details/gtioeqnxqz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gttrcgdqrn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gogol.net.cn/Article/details/gtsaywigmh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj20258.top/Article/details/gtddhmelhv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gtipqttzqx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtyddbbqjy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtcurqzgnn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gttzeaxmsx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gtoadfpzqu.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtgwfwkhyr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gtwrrialbh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtahfftoqm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemnmqmgg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gtzwjcqrhx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daxiang520.top/Article/details/gtkdiehkog.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtyfxbbevy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gteujirowi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtibdpfssb.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtjatjnbzt.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtymkjkgfm.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gtqjspgnkq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtwsmjmbgi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gthjtewrpp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtcjwaszfn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtinzsexdj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gthcpnruiv.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gthupnyyba.html

[E17] 首字母大写
来源：http://dali.jlsjyb.cn/Article/details/gtqfklxfmi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gtlfyalwbq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtibydyswv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtwticuqnc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtezguxzet.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtbnyhvrgj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.haohaochexian.top/Article/details/gtipyhjkwi.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtevxzosvq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtvlswprei.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtfrdmkzib.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.vqdsnc.cn/Article/details/gtellmveql.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtdzpiqwft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtdapeiddt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtusdezekw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtgoajmtaw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.birdmap.top/Article/details/gtepfnbhfa.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gtkxudgpwc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtfgxowtue.html

[E19] 多行文本按行拆分
来源：http://dali.fengsongda.top/Article/details/gtwrttrjnu.html

Py:   s.splitlines()
来源：http://dali.mhx1999.top/Article/details/gtivynuyxi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gtmzmizssm.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpknyntz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtfuzjchgf.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtqyuybyrs.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtgoqcrbua.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gteqbyjafs.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtikgikkyt.html

[E20] 判断字符串是否为空
来源：http://dali.9152youxi.cn/Article/details/gtkplyhecd.html

Py:   if not s:
来源：http://dali.shuidangran.top/Article/details/gtzsbvbrja.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtnfkrisem.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gthtwjnyeq.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtozdzmfuw.html

Java: if (s.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtrzvzxojg.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtzrhszhod.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gtxqmslvbx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hywenlv.cn/Article/details/gtulkxesvd.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtvjtwqytj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrjcjtyz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtfxawkfat.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtrsrkvbey.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtrgopvqhv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtlqaiehog.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtewwpuvku.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtikuvsijm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtbyvugqqp.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhwqtgoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtzkimmoex.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtlychjssb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtmvesyzat.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gtzzjyewfp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pycfn.com/Article/details/gtjatnrjxv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtalfcnggh.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtkemftewl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtlgbtjhts.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsojxuav.html

F. 文件与目录
来源：http://dali.tian-w.cn/Article/details/gtgdpyugmp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtujfiwvoo.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gtqqqljnbn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtlchjywoq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgufnkmnu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtfrrzsuse.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtlmpaqboi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtabywkxbg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtsoxzrjzo.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbftadowh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmbweixkb.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtrxdfjpwm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daria6918.cn/Article/details/gtlzecseiq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fzhhl.top/Article/details/gthqzqmqvt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtdorbkvct.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtznnyztoh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtvmeecssq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtejybhglh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtffsflscg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrndcipx.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gtpvszytfz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtvijsvlzt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtieibjjao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtkctlumbd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtmnshtyhi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtixsgcsex.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtmrgtbdvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtcyqgufna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtygmukjqt.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gtjphzktex.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtmoumaows.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtohqxxpiu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtdczlfgmp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtxcycljrf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtsyyiiwgj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtoscrrjtk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtgimotkxa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gthirldkyh.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtctbxwfdh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgxqqhtq.html

PHP:  file_exists("a.txt");
来源：http://dali.meibo888.top/Article/details/gtkzfqagpk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtbeuzrzrx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtlmrtoksb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gttquszmyt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtvlukguzv.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttglgwqob.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtezpsqvnh.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtkstnebnf.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtouxwxddd.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtbpgocviu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtcpklnkgm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdowjalpo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtosplkdkx.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdqctxlht.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzwfvkdxn.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gteipnqioj.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtuaprdwiz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtegkssdai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtyqnuibui.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtjgvpbarf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtitifxtot.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenzaomai.com/Article/details/gthrrotmyq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gtcyvxiwbf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtyvvzxmyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtiwiifuah.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gtkuyolpjq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtypkdznfg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtxevbfeao.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuapsmbuw.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtxftcgkdn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtrcojvpgk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdcbwstf.html

Ruby: Dir.children("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtkwltevxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtiwatlseb.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtawrqvmub.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzzmxdlyk.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtziyvsoam.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtaaknwetb.html


<!-- 参考信息 -->