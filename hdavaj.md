代发 wailian999

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gt2eyslnyyh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.316326.xyz/Article/details/gt2uiewkjco.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ethhutan.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2lagklbfk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zdqjudy.top/Article/details/gt2nubybefv.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2ixdqwhlt.html

JS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gt2culfblqk.html

TS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gt2omlhhhzd.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gt2snvwfntm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.meibo888.top/Article/details/gt2zsrsxevk.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2ajeljtgy.html

C#:   string.Join(", ", list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2appihpsq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2pvrfknwr.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2wmudwqct.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bohvugcj.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2kncfgsdm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.svipenyu.cn/Article/details/gt2tevbpzof.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gt2gmprrbmn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xloxnioh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2oxuwshix.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gt2tqasmcdp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pengpengdd.cyou/Article/details/gt2unlxkldm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.svipenyu.cn/Article/details/gt2uaaecwnj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gt2fsbhlggs.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gt2tvlqblvm.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2qvgyolan.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmoavdkv.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beifsjxo.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2cqqpqrmn.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzpsqlek.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ehwqpu.com/Article/details/gt2dtqihfqs.html

Ruby: "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gt2vhanohqq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gt2uclwhudd.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gt2ktfixdfd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gt2ktylzekq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjrsctmn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zuhnhfdn.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2oajgwpyx.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdplwmyt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2kssjrepb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gt2rxxldkog.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gt2rtycopxp.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gt2doqakger.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cashguo.top/Article/details/gt2xtmgzwyy.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gt2weqrslnp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwxphmda.html

TS:   s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gt2icwpuiyj.html

Java: s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gt2dmksuokp.html

Go:   strings.Index(s, "x")
来源：http://dali.yj202588.top/Article/details/gt2icmyqlnr.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gt2kurluzlk.html

C#:   s.IndexOf("x")
来源：http://dali.redwolf501.top/Article/details/gt2rsxfrcao.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhongyouzk.top/Article/details/gt2einsdxqe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbetqpz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gt2ksnkbztg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2xfqrnmtx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jianghu66.top/Article/details/gt2ipxyfnko.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrludlww.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gt2eklqltmj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2kznjdehf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aibaodan.cn/Article/details/gt2gylmghfp.html

[E06] 替换子串
来源：http://dali.nanxinkj.top/Article/details/gt2yktipiju.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2rtbdjhzb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjhsbtru.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2arbirxuf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2ahmunfen.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2dayrzaqw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gt2utaplbuo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2xscllter.html

C#:   s.Replace("a", "b")
来源：http://dali.ivvv.top/Article/details/gt2qsuanrbm.html

[E07] 按分隔符拆分
来源：http://dali.yuxming.cn/Article/details/gt2hwthdany.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.redwolf501.top/Article/details/gt2ryjrlxth.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2gdmeqngx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xinyue.icu/Article/details/gt2qhedzkrb.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gt2yusawmch.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhongyouzk.top/Article/details/gt2tmucrbqa.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yongpay.top/Article/details/gt2wrypdytj.html

Ruby: s.split(",");  s.split
来源：http://dali.ydzc1.top/Article/details/gt2umqvlcnq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qvnilqth.html

[E08] 数组按分隔符合并
来源：http://dali.gogol.net.cn/Article/details/gt2groneior.html

Py:   ",".join(items)
来源：http://dali.sweek.top/Article/details/gt2bcaxwwhm.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gt2vhpsqpox.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2fcdiaalp.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2dqeivoss.html

Java: String.join(",", items)
来源：http://dali.gzhubu.top/Article/details/gt2blipyuxe.html

Go:   strings.Join(items, ",")
来源：http://dali.cqqwz.cn/Article/details/gt2qybihjif.html

Ruby: items.join(",")
来源：http://dali.shuidangran.top/Article/details/gt2hlzersra.html

C#:   string.Join(",", items)
来源：http://dali.ehwqpu.com/Article/details/gt2hiiwcvtb.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gt2utwtstnb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntooorsw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfusalod.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2vpheyykv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2sgbwbtih.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gt2bhqyzdsa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2pfgcosxn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aibaodan.cn/Article/details/gt2xyconkcr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2uzoeewfp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2gszfuxrt.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2qrydifvc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdhtqalg.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gt2rrhhoony.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2jvcpdcwd.html

Java: String.format("%03d", 7)
来源：http://dali.chenlongwang.top/Article/details/gt2hzcdwdxg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.snrcjt.cn/Article/details/gt2aeqpdnvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gt2jicjqfka.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmfmbgbm.html

[E11] 反转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2snzjmbsa.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2pqaigxie.html

PHP:  strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gt2zfxtpmqu.html

JS:   [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2oayxwaiu.html

TS:   [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2vhaasyfx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2hqtodryu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.aibaodan.cn/Article/details/gt2jxlarpvh.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2ldskzcwb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2jvcccspo.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gt2hahgojxx.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2wzteatuu.html

PHP:  substr_count($s, "a");
来源：http://dali.hammf.cn/Article/details/gt2bilnzpyn.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngxsxmbw.html

TS:   s.split("a").length - 1
来源：http://dali.tianlin.xyz/Article/details/gt2actnihlv.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gt2pgzddfhm.html

Go:   strings.Count(s, "a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsgneolm.html

Ruby: s.count("a")
来源：http://dali.pycfn.com/Article/details/gt2shxmdjyh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258.top/Article/details/gt2dxceowci.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvlsorso.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gt2uhzgtcrn.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gt2rmaztbmx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cashguo.top/Article/details/gt2aqyubuwe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2vhgomvbb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2zmviwjdf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2pheaajhl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gogol.net.cn/Article/details/gt2tdwawmso.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.pycfn.com/Article/details/gt2egcsifng.html

[E14] URL 编码与 Base64
来源：http://dali.shzxlz.cn/Article/details/gt2drhvizvt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yongpay.top/Article/details/gt2gsywxhlt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gt2ivrdneyx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkgbtlwy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yueranfly.top/Article/details/gt2tcqnybbh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2fhuiidqa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gt2xgwzwbyb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnauxqqt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2xaqfsxwj.html

[E15] HTML 转义 / 反转义
来源：http://dali.jlsjyb.cn/Article/details/gt2fvaxvbki.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gt2rabdtkwv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2rodutszy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.guowangkeji.top/Article/details/gt2dsvjzyes.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnpcauo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2gakdbbqx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2lqaxilig.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vvitfkkl.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2htbdbgyp.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2bchogyyt.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gt2xsitbqby.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gt2jwzxlsmr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2ooibplht.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gt2xdpijvni.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgfvecze.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yvedp.cn/Article/details/gt2zehmwvto.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2cerbqzpu.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljnohobb.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gt2jzwemwpg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2znwzfbjy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2gwwameqq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rmzihznk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2sfljqdeh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jesvkkxy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyapzatm.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2whfmpuqw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gt2gjnjlzkw.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2qiazmddh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2zwtbeasx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cdnleiting.top/Article/details/gt2xejmncvx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2lfzzdncp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykpkyalw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2dbmzjwex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2dnjvoxwn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aizwys.cn/Article/details/gt2fqwktyee.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2nmtclimw.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gt2yaumifss.html

Py:   s.splitlines()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyaxqdse.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2puxliyri.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2ckkopucu.html

TS:   s.split(/\r?\n/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlkogjvq.html

Java: s.lines().toList()
来源：http://dali.jyoumei.cn/Article/details/gt2pypadwcf.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gt2bqzattyk.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2gvfqalav.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gt2miuuslji.html

[E20] 判断字符串是否为空
来源：http://dali.xuanzx.com/Article/details/gt2rjeqcixe.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2kdncbhys.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.quarkkingdee.top/Article/details/gt2yckojhmd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2grcishtc.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2wcwgwgtk.html

Java: if (s.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2njnjybik.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2cmbnzwlu.html

Ruby: if s.empty?
来源：http://dali.pengpengdd.cyou/Article/details/gt2etmgtfac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gt2icaluomn.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2vwxfrvvf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2akbxavre.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwnqwoym.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2qrkroikp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2prnicmvd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2pgxmkfbo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gt2vpevmmto.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gt2uzmzptta.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2sebjoero.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gt2tdatpgoh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2orhgjgpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2wqrruddx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2pqwgncyl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2fzngadeg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gt2jqnqogej.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gt2kwdhobgx.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gt2izjcmevh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhgesvud.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2uoyearjq.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2mrevrhrh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2xnwssvfm.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2jcusmqcl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gt2frfghrgo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2bldltqvl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cqqwz.cn/Article/details/gt2lyqbpnlo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2rrqvzoge.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gt2afgddcpt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2wdrnbsmb.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2jymazmlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2tzlktrnj.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gt2aunuglsh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2dechilys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gt2vvvxojoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cphpsvcf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2btiibwgb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2rxnxcoij.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gt2yycuajnf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpehhvbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gt2uwwqofkw.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2lpkgxoel.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcncasdl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2mhijyhao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2ubzdejhd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2ytkzdyke.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gt2bjowenrh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkldiuxm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2btkliasw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2cohsygql.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2gfxvasto.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2xgmkrhzn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2igovjkqz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2srsdlepa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcffabws.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gt2zbltamdq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gt2kytrwajj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gt2yyftuadk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2oxtmebrt.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2zybgzcyu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yongpay.top/Article/details/gt2hcljedid.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2ifdgyhlt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jelhdmdn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2xshkxtjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2itmnlqgj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2vzboonca.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2pyamckrb.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ubkitygn.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbobvagi.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzhoedij.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axetbgoa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2jadgutpv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2kdsathxm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2ruubwbgg.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2yvmobatm.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nymvbkpq.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2taolewod.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzfbzqja.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2zwonghbh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gt2mtekjzqn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeubpetx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2nrixtmha.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2tantrpbj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnfrypqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2rhbtjygb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2tjydykaa.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2ururxfvy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2tgqhxnhk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2vqczdqgt.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2izqlpxen.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2gsfupukc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2lohexnns.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gt2erakdxps.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkogwtqi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gt2qrnetjoz.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqwdgyzu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2eqxcguea.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2wqbqgpih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2cpknwdov.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2vaajagzd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2fuppxqws.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2licmwjmo.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vmirndrl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2sgqrrbmn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gt2ynvnghkp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ikfwvkhq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ykalhqwa.html


<!-- 参考信息 -->