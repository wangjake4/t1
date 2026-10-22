代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozxokcwb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gt2zsubuxpq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgzscehu.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gt2cxwtgdmn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gt2biqntzgg.html

PHP:  implode(", ", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2rxijvmax.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2whumfrdv.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2ieworxnh.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gt2jjeaffhy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.aibaodan.cn/Article/details/gt2tlpiqyyv.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuxxeseg.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2nwxrfhts.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ecwouigt.html

E. 字符串处理
来源：http://dali.iojbl.cn/Article/details/gt2lwooqrtq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sysjysld.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2fsaagtqd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqxfdrke.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocwuzsxd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2feiuweyr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tian-w.cn/Article/details/gt2ygaqtwhz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phqhicdf.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gzhubu.top/Article/details/gt2apyrhfgd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gt2upvdvkrn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daria6918.cn/Article/details/gt2vejphhql.html

[E02] 重复字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmpdrwog.html

Py:   "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gt2axjcvuzo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yongpay.top/Article/details/gt2rugyaorn.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2lpdlojxy.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2wpkrkjti.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2segmnkxn.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2qepvzzyo.html

Ruby: "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gt2sevogclv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gt2fehijmic.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2mutitvya.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sweek.top/Article/details/gt2fluonytq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2kzwvyoub.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.0kj1m.cn/Article/details/gt2gsclmyer.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2lboxjqdi.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gt2ksujkszq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sweek.top/Article/details/gt2gbdktlom.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgufenzy.top/Article/details/gt2uwzysinb.html

C#:   s.Substring(1, 3)
来源：http://dali.dianchejie.cn/Article/details/gt2gifrofgt.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gt2uswrgguj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2zielsupx.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gt2fhbixgsf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gt2pfswyyiq.html

TS:   s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gt2jobkcszo.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmxryun.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpzjxtp.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2ddyxunxd.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2efjnnvfw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangdashe.top/Article/details/gt2mndrobso.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gt2fjdiqaqe.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gt2vyoangfa.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2gussxljc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tianlin.xyz/Article/details/gt2yjozdwkj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gt2nubtmazj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2veajxree.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gt2dymqpfot.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xinyue.icu/Article/details/gt2xxwunktr.html

[E06] 替换子串
来源：http://dali.zhixingplan.top/Article/details/gt2uqczliav.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2zyhrrodv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jianghu66.top/Article/details/gt2reipsedm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2hnlaatno.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2gtztwyzr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2ipytjsgs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2xhyfabxh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2yhkcdoou.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2thqypckh.html

[E07] 按分隔符拆分
来源：http://dali.sxryk.cn/Article/details/gt2vzxzrwbe.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oodlylvt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gt2xztgrvfh.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gt2mkxqfzwn.html

TS:   s.split(",")
来源：http://dali.iojbl.cn/Article/details/gt2ogggejpd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gt2ikhakxvt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbckpuhg.html

Ruby: s.split(",");  s.split
来源：http://dali.smart0.xyz/Article/details/gt2gxkvubga.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenzaomai.com/Article/details/gt2vifajokr.html

[E08] 数组按分隔符合并
来源：http://dali.sufxvd.cn/Article/details/gt2ffecpoie.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmvjsddh.html

PHP:  implode(",", $items);
来源：http://dali.nanxuanxn.top/Article/details/gt2vmmodecj.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2atrqwrnw.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gt2srowszka.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2omkfqemx.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gt2wjpazstj.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gt2qujkdqtr.html

C#:   string.Join(",", items)
来源：http://dali.aibaodan.cn/Article/details/gt2bwgjwegd.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2xtnqmlvx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ubbhikmn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.nanxuanxn.top/Article/details/gt2okbdmdtw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gt2otkgcgsg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sufxvd.cn/Article/details/gt2orsqqahi.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.0kj1m.cn/Article/details/gt2mepqvqng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gt2bfrbsplb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2dbljynie.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yongpay.top/Article/details/gt2vztudxot.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhengqikj.top/Article/details/gt2xdnbmjyr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2diucmrav.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sysykeji.top/Article/details/gt2nlyrkhqd.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2hyqfzjhy.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2knqfhmsq.html

Java: String.format("%03d", 7)
来源：http://dali.c1oappe.top/Article/details/gt2vdgubppp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gt2beosycvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekpctaau.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gt2zofxitsp.html

[E11] 反转字符串
来源：http://dali.ivvv.top/Article/details/gt2iujohnfq.html

Py:   s[::-1]
来源：http://dali.tian-w.cn/Article/details/gt2kjcvdllm.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2nmqcrvvc.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2ziznedeg.html

TS:   [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2dqhpryos.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cashguo.top/Article/details/gt2twelbsji.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2egayfhmz.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2zcmdlbfs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2rtejshmc.html

[E12] 统计某字符出现次数
来源：http://dali.yj202588.top/Article/details/gt2vamjyikl.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdjquwvt.html

PHP:  substr_count($s, "a");
来源：http://dali.gzhubu.top/Article/details/gt2trwtenre.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytnyogiz.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gt2angtrohl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gaohongyu789.top/Article/details/gt2flohxhjp.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gt2kubzmkkb.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gt2wzolgtdo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gt2tgkyuooj.html

[E13] 逐字符遍历
来源：http://dali.sxryk.cn/Article/details/gt2rdcfuyyq.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gt2eoklxovm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gt2kegqyiio.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gt2plzkmfvp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rxwdowkp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2kyxanqhc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gt2pujqukxf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gt2rwsdtcdv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gt2cvjjhgoj.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gt2tkegugnh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigufen.top/Article/details/gt2vspqdmmx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2ohapxtgi.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aljyblig.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gt2dvqstuka.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2vevcgzuc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.dashuyun.cn/Article/details/gt2qogklkga.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2flqvfyio.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2uyscssry.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gt2sckytqqj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gt2vylnlqzg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2xgswwhly.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyhusdzf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yonumen.top/Article/details/gt2yflvxokd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.kuanghao11.cn/Article/details/gt2jjuxywzo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2kvrcbzbp.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2bxrypbfw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2bhtrhxfj.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gt2dlfrvuks.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2qozbjndu.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gt2mupdznbp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2mabsjkse.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2pjdxrozg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cqqwz.cn/Article/details/gt2rnuygcac.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gt2ochfeqsp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cucudq.cn/Article/details/gt2wmlkzmku.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2loidbxfl.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywunycxn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2sjgrymxc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akheyhlk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2wxidjlxo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gt2kidfhsjm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kijqqkye.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gt2buwvrgok.html

Ruby: s.capitalize
来源：http://dali.smart0.xyz/Article/details/gt2ycyhmmqz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gt2ubzyvohw.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gt2gkhkossh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gt2ikgoqibr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gt2wqzblije.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2yvgusswz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2cixdtzmi.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2gbzgyjsu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2gdshldvj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhoulong.xyz/Article/details/gt2gceypqkc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2mjydlnmn.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chlqkcem.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2krupunaa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsslsjws.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2euxojhsn.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2wgrwgehl.html

Java: s.lines().toList()
来源：http://dali.birdmap.top/Article/details/gt2pxcldqyb.html

Go:   strings.Split(s, "\n")
来源：http://dali.gotoacloud.top/Article/details/gt2cdbaifgg.html

Ruby: s.lines
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eyrqwodn.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2lmotucrl.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2mzhcoklj.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2nciugtkc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2jbmmsfty.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2cyxayarz.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gt2uzegxolx.html

Java: if (s.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gt2ncpnpgtw.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gt2mvdnjtkv.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gt2gmsexuzg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2bnfknugn.html

[E21] 超长截断加省略号
来源：http://dali.hnxiangtu.top/Article/details/gt2sixyogxh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2velvwoht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2adbvxnvv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2dpulzfqk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2ofrbxitm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2tvvdrojb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gt2ijkwntxd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxncpzh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gt2rkpgbtdx.html

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gt2dbqzrszq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bguqrwed.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2hciccack.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2kdignlgp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2yshphjpl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gt2omhrbqaz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gt2psopckha.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2gqxttdik.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2tonlvnqk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2yxwzdqoi.html

F. 文件与目录
来源：http://dali.sweek.top/Article/details/gt2gasdwmov.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2eswcnfpr.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gt2pdfzktwo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2hkzonvhv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2zhalgbaw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsbunvkm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdjzcxcl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2xhjooult.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gt2vxsfmtnv.html

Ruby: File.read("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cxxjrgez.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2knvmxbbx.html

[F02] 逐行读取文件
来源：http://dali.meibo888.top/Article/details/gt2awwtpqum.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2rghcynpr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2rsvhyiiu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2cejsyosf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2tabirmkk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2qqhqnslz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2zggppeya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gt2xpfjkhql.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2nkbbxbfj.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2vkjldpmn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gt2munahvjw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2nilcyiwa.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2tbulzxxe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2iwmaoxcl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2ecfcjxsx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gt2syvtdjqa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykcswkeo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2uaqeyttr.html

[F04] 追加写入文件
来源：http://dali.hnxiangtu.top/Article/details/gt2fhvderro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gt2njufqxfl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sweek.top/Article/details/gt2uaxhjnuf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2mttasnkr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2tjimayei.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2kjczlltq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2circyuga.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2spudythb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2ticthwew.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2exianaex.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2tkipbgba.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alrcyouq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rdrdgzog.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ilpyybyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2kzkyurwf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2frksotyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2pfxuwdux.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2abvllafi.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gt2vcwupbqd.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cydzsdgb.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2zqoiacrt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vhwpfrtk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytofmqnk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2umyfbflh.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2wmyqhdgi.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vrzqwrku.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2jyenmvea.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfvlfjxv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gt2ardnodur.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkhosomk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2ehgxxbrf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2fggikwjk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gt2eucnuwcc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2coqgqylr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2dkzgyywp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2kxsjdalb.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2odfgjhoe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gt2zylutwzu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gt2uiaiybuw.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2fonqkpfd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2geugcjkm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2krmvnoea.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ouemyovf.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2swtxsvbw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2rtstruae.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gt2ifiicijv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2szycgfzt.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2sflbscrl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gt2nzhkmecp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2ksgxomra.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2uxulwvwh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2dzabrkrj.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2ycjqbrgp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2vgweqgpx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srkkeztx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ukmchjtm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2wuwitsze.html


<!-- 参考信息 -->