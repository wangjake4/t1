代发 wailian999

[E06] 替换子串
来源：http://dali.haohaochexian.top/Article/details/gt2cpbqlhky.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258.top/Article/details/gt2vrdholgn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sufxvd.cn/Article/details/gt2ghrowlny.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2csyqgdjm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gt2ijueeyke.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2nmimqjgr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwkfexyx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2nhlmvaxo.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2kvdptfqt.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gt2cqvnbnlq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gt2mgxuptrv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2rucbuzwm.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zycfv.cn/Article/details/gt2bkogsuve.html

TS:   s.split(",")
来源：http://dali.ehwqpu.com/Article/details/gt2andnzwzp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gt2iyiwfswj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gt2ovypctjr.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gt2vefoqilg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cashguo.top/Article/details/gt2umdfekzy.html

[E08] 数组按分隔符合并
来源：http://dali.meibo888.top/Article/details/gt2cmpmhege.html

Py:   ",".join(items)
来源：http://dali.cucudq.cn/Article/details/gt2quuvmuuo.html

PHP:  implode(",", $items);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhxtkde.html

JS:   items.join(",")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbznuuov.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gt2ahaimnbl.html

Java: String.join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmphoetn.html

Go:   strings.Join(items, ",")
来源：http://dali.yuanzhike.top/Article/details/gt2qjjmnusz.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxqupkhi.html

C#:   string.Join(",", items)
来源：http://dali.meibo888.top/Article/details/gt2udviuova.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gt2eabbbwst.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gt2xvdkzgut.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258.top/Article/details/gt2dgtzdlyq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2meudckcw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gt2diuhxclv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2gkigncgb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2pqkuacpp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2wsaxetiq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2ziblphtc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yongpay.top/Article/details/gt2sbcanvxu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2smjrdaqy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gt2kwdwyllr.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csciudjq.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2uponkhxj.html

Java: String.format("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2ucobqylc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2xxbemokv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sufxvd.cn/Article/details/gt2pjhyedqs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zycfv.cn/Article/details/gt2khnyesjk.html

[E11] 反转字符串
来源：http://dali.sxryk.cn/Article/details/gt2lybayljw.html

Py:   s[::-1]
来源：http://dali.daxiang520.top/Article/details/gt2nwmliheu.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gt2icpsrulo.html

JS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2tqhwdysm.html

TS:   [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2axxkurmv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2nrvcnfkq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2cpdzxqpk.html

Ruby: s.reverse
来源：http://dali.sweek.top/Article/details/gt2sgromtgb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2zleaatmh.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gt2dfpswpfz.html

Py:   s.count("a")
来源：http://dali.sxryk.cn/Article/details/gt2wvkxioud.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2dvaxnsir.html

JS:   s.split("a").length - 1
来源：http://dali.yj202588.top/Article/details/gt2ldulttzv.html

TS:   s.split("a").length - 1
来源：http://dali.redwolf501.top/Article/details/gt2dzjppugp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gt2wpraisqg.html

Go:   strings.Count(s, "a")
来源：http://dali.tianlin.xyz/Article/details/gt2qnwybghx.html

Ruby: s.count("a")
来源：http://dali.redwolf501.top/Article/details/gt2yowltppp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gt2klcdvckx.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gt2rajbtudv.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gt2jsnrlxqo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gt2sbuhrruv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2rkvikqxs.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fztnztnf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2rufhftsv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gt2erhnsoin.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gt2kkgnxudj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2jsnajvdv.html

[E14] URL 编码与 Base64
来源：http://dali.gogol.net.cn/Article/details/gt2lpbqimbg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gt2krxhnvga.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangdashe.top/Article/details/gt2sgpdwdny.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkzlkzlr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gt2jydjwzdv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2pqaziigr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jiagoushi.top/Article/details/gt2bdwlenwn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gt2dubmkqzh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.316326.xyz/Article/details/gt2ogabnkgs.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gt2sufeobqx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.daria6918.cn/Article/details/gt2zujrwigd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2iqynrcpv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgjajuis.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gt2ahsjwyss.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2amznbril.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fzhhl.top/Article/details/gt2jgulontg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qrlqoztk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guowangkeji.top/Article/details/gt2gevvtycm.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gt2kfoddazd.html

Py:   f"{1234567:,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtkephqn.html

PHP:  number_format(1234567);
来源：http://dali.wangdashe.top/Article/details/gt2mfbwiawz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2xobacoby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqywyduw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqezuvlr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gt2zkmacgvb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gt2grafrbma.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gt2vtjnuigq.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjyqpmoi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2lajkjdqr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gt2nazphone.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2gdekrgur.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2jjixhmoq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxsxqcfz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2grjobljw.html

Ruby: s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgitbiba.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hongshengwenyu.top/Article/details/gt2haihodlf.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gt2vpfwbfci.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2fzrhjcnm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gt2unerqela.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2zsxqoowe.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2sgesoaxs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2quofyjba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gt2nrklkqrk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2jvwibwxh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2dmikgtda.html

[E19] 多行文本按行拆分
来源：http://dali.9152youxi.cn/Article/details/gt2bpgrthfu.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2hyjomunb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2mwdfmvvw.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeoxcxlq.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gt2pwlogcyp.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2dcpdeafk.html

Go:   strings.Split(s, "\n")
来源：http://dali.yongpay.top/Article/details/gt2yfsaggrk.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilvrloqd.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gt2hpllzevk.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2qvmoijzd.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2stlrnvmd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gt2gcdbrraa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2mjbtdrjv.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bvujbmzf.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gt2shvctyjc.html

Go:   if s == "" {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rceednix.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2xydvhxec.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gt2inhlslvo.html

[E21] 超长截断加省略号
来源：http://dali.gaohongyu789.top/Article/details/gt2obycsbwz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2ydzzsrol.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pilwggjq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2lboglcyy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2ixytjgsn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2yhkddydc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cvihugou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2brqwcewz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2qqtkfzwh.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gt2csyfjjkb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlnfdtle.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2zluitslr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2lokcqcty.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2hflcyeew.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2xyzudygm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2ebdsoijg.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2iekzhpjc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2icywwktn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2einxdntl.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2ykrsobrf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2pytqktxa.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2hkgnnpbi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijckyswl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdyxqypl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gt2wgkrzyqr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2ellwijys.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2bgpauxsj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2vfmacljy.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2zvuyctmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2jvlsqynv.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gt2lvsabzbu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gt2zyitjlrl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2wkcqizsd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2jxzbrplc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqzywrut.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2avanzrxn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gt2hzsfcgpc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2rmlmnolh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gt2yivkwgqr.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsylkfop.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gt2ijjrvmrz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xoejcvpk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2ctmpxmri.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2jopwqnbg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2logiacoe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gt2mftdrijf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2wndnutbl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2olmtvpix.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2aohgwgyp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2mldtemld.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gt2aydylnai.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2qdsjbvtc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2khfozfkc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2sqlbbazi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gibwhedg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2wtmadkow.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2iahrhwsh.html

[F05] 判断文件或目录是否存在
来源：http://dali.cqqwz.cn/Article/details/gt2notkikav.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gt2aacjfcok.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2xrozhifv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fspbhlgg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qwuexlyy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfifkvyo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gt2uvyrbvkj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ygkmgtee.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xogpvaul.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2grmpsdsi.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2xivccxie.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzsqtngj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2lnizycen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2kdgvdbao.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2sijuidyy.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2mdqjpxgt.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dufwjggi.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2ueloqsxh.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2lomketzy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2gbkcbfns.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gt2pxzttave.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2nkoweuzi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgqvvzop.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gt2eljcwmac.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gt2tffloisp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzwgeqvq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2xwggzcww.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gt2cwrgvvht.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2ebemvwdu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2qittvnpd.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2zcnqjrqq.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2siqrkwbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2lpfsfzov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2iqtbfhup.html

Ruby: Dir.children("dir")
来源：http://dali.yvedp.cn/Article/details/gt2xaegjamq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2nmkesppl.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2siuipcsu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2bncomhza.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2xwnfpfls.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2wkbkskbm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2wthuuqds.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2bfafuqwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2tqmyvjia.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2zlxthvly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gt2svficrfe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnccegck.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xhinjjnv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2exburalf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2jypknziv.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2hixkpkdd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gt2fqzodtjf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iptkfbjf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2cezofoim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2bgjgmtag.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2coxvmpho.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2avklsxkr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xukdbbbw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zxlgqoix.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2opmlqatz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cczlpxyo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2rchxlmkf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2clbzxfsy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paugeerz.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2bmjqktsz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2fmmvzjyy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gt2vyazciyp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idhuoymp.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gt2ileizrdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2arvgqdef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gt2sgszihhe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2vbcgbjlx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofoaxesz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wgdnjvbm.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2lkofnloj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wupfcbmk.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2osnnvdpd.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2gyovtbin.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ppdxkfzu.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2tywuzbzp.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwcunedm.html

Java: class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iufwqbjh.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gt2nbaemhoe.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2yjbfpdqe.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2qvxwdfkx.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysgekliu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gt2srxqmkuc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2doqfpdkw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqqocypf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2nanxtsxl.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2pywoyagp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gt2szhhhxot.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gt2mixwkvlz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2asvitypr.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2ebngcfqs.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2fynoacmc.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2ztawjnku.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2bhbynrgg.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2etqddmae.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2midibwdn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2barznpyc.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvaykaxc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2ljypkvkm.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2vlkpdhxa.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2innsoowf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fafcmfor.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2nvdaukeo.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2ucwnpmph.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2depgmohi.html


<!-- 参考信息 -->