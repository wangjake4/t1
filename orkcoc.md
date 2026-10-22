代发 wailian999

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkkcuylo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj202588.top/Article/details/gt2obsakluz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2giovipjc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2wgpgsovm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2eaykswfw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gt2femjgxai.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trgvsvvx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2sjvydepu.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpxbmgug.html

[E07] 按分隔符拆分
来源：http://dali.meibo888.top/Article/details/gt2daamikcg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jinqigufen.top/Article/details/gt2yfskxuco.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2qpelfcrb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gt2ajjvcooc.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2gtigbnai.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.birdmap.top/Article/details/gt2euhfdpra.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gt2psaqkjwu.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gt2bfmlejdc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xinyue.icu/Article/details/gt2vidhreej.html

[E08] 数组按分隔符合并
来源：http://dali.xuanzx.com/Article/details/gt2jlofckyp.html

Py:   ",".join(items)
来源：http://dali.wangdashe.top/Article/details/gt2weczmygq.html

PHP:  implode(",", $items);
来源：http://dali.meibo888.top/Article/details/gt2tpmbaghr.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gt2sdxhpauj.html

TS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlbfsgfv.html

Java: String.join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gt2vmdgojhj.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2shpnwxse.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2brtyubtg.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2mbyhyjtf.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gt2ywxcysyo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gt2sjvmrepf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gt2gjomdbno.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2bkrlkexv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gt2hxwfjclm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2lfgywirc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gt2vapegpyr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yddmjbxm.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2jtvjzrpv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2ibyqjxsv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2jqbwiayx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dianchejie.cn/Article/details/gt2sifxpgbv.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2czzpoihx.html

TS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pymlgxja.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gt2dmbullru.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2pltmxnvf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2yfonusni.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sysykeji.top/Article/details/gt2ledecefm.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gt2qrpceovo.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2xfkxtdfw.html

PHP:  strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2juesvtsd.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2qttbeyan.html

TS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrpxxpdz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2kkbjljhn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daria6918.cn/Article/details/gt2rqafvups.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2nwppvlmf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gt2qaagflis.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2lyikyfji.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2xtuvgsds.html

PHP:  substr_count($s, "a");
来源：http://dali.nwbrower.top/Article/details/gt2vwvejugt.html

JS:   s.split("a").length - 1
来源：http://dali.yongpay.top/Article/details/gt2mqvrphsc.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2pjsaimgs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ccfibcve.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gt2rflgwlsp.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gt2tiupwrgh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2aqyeayco.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gt2nkoyjrdu.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2icgxikqx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cheryme.top/Article/details/gt2wbthxvst.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2liuxjdjt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gt2ldzyceue.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gt2ooccsrzp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2nsuoiisg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuanzhike.top/Article/details/gt2vdojcibw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gt2iqfakhek.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvbvqnhf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nwbrower.top/Article/details/gt2vamaqwlm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.smart0.xyz/Article/details/gt2znkqtswl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gt2cchsowpc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cheryme.top/Article/details/gt2hugmmljw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2rfpyvikm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gt2loeqlttw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2mpzluqng.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.birdmap.top/Article/details/gt2ycuzxuqp.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuxming.cn/Article/details/gt2qvrufvww.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gt2pvzlackd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktgowkvt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tanke756.top/Article/details/gt2pukbafch.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gt2tzrmhciw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tianlin.xyz/Article/details/gt2ozqaoctm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2rneegwtt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sysykeji.top/Article/details/gt2ychlqwxv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gt2fmipvkgi.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfrnywli.html

Py:   f"{1234567:,}"
来源：http://dali.0kj1m.cn/Article/details/gt2ymyxdolv.html

PHP:  number_format(1234567);
来源：http://dali.smart0.xyz/Article/details/gt2chvtwdov.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2dnxzempq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gt2rbndxkgl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyzcndhb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.daxiang520.top/Article/details/gt2brjsklua.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2icxhytvt.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxrseywm.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gt2rjigfygx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2wqyzrbei.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gt2tmxsbelv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2anzulhmn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2yczdlpze.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2imujvnke.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2hnuwxbgj.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gt2hfugqozx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2zwjtnfef.html

[E18] 模板占位符替换
来源：http://dali.hfpthk.cn/Article/details/gt2afugqded.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gt2tapjljuc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pycfn.com/Article/details/gt2hhumhrkx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlkvlbei.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2tfwsjguo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2hdeoqeii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2xozczxrv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gt2hmshizxq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gzhubu.top/Article/details/gt2lzaiurob.html

[E19] 多行文本按行拆分
来源：http://dali.xuetiantiany.cn/Article/details/gt2srayopht.html

Py:   s.splitlines()
来源：http://dali.xziqi.cn/Article/details/gt2ftkupdmi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2cvbczyaa.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gt2ifmyfzxi.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2cjiaxdkm.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tuyjhrms.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovjkjjwy.html

Ruby: s.lines
来源：http://dali.yangfankeji.com/Article/details/gt2npfrkzbz.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2acfekgxi.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2ymsanxuj.html

Py:   if not s:
来源：http://dali.hnqzz.top/Article/details/gt2zhaxaztk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2efncuvux.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uddbvejm.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2ucmlcpcb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aknvgasy.html

Go:   if s == "" {}
来源：http://dali.cashguo.top/Article/details/gt2jqcdzzit.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2qgomnqke.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gt2sihfmqpt.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpaijdvi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2tlgggsbz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2wujxezxr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2yramhtof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2xvezktqe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2hiddadfl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnjgjuxc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2blxbkoag.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2azorneun.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckxfffyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gt2oqbxpkoq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggyndxli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cashguo.top/Article/details/gt2fgczuwba.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2pubvcsbd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2kxdkhfbu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2xmthaxex.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2ilzhzueu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2owkbmcdd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2anfvigec.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gt2tbnylvdy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2aksrkpqn.html

[F01] 读取整个文件
来源：http://dali.nwbrower.top/Article/details/gt2uvxpclqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gt2mrqguzha.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2inkegnah.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.mhx1999.top/Article/details/gt2bodkqcku.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2jwxdtkxv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2ppafhqqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gt2njdzmiaw.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnrmwkul.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2sjtlnupl.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2zxcsuebw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gt2nxsyamli.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2eegswtps.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywxifyvk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2pjqodqkc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2ezrhfyjs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2umcsbbck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gt2dehkebuu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lqiypflm.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2zrbjvyvj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gt2suredhzn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2rmfhniee.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqahcklk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2noeebsjm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gt2fozebdej.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2nbbfhnkw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gt2wtwnmfhj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gt2ktywfbhi.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gt2gwejgfsn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2ovikfhzn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2udnzkpsp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2tkmhwigj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2mkcxbxsd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gt2highodkp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2hvssmhaj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gt2bjitcqtx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2temnsgvm.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gt2extwfcmu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gt2naghgcml.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2asepaevb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nqdhetnu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2chsjnypn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2ghikghej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2tygptrff.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ctubyvhw.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2auzfwiyz.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2ovqakcqa.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saugqbbt.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cijqzcje.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qmpllnqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2iuxsdgho.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2scchcqbn.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2xkwotlwb.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2uuibjplp.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2nbwiyswb.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2bwttzlum.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2mvrtggod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gt2jzarbajf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gt2jdvphngk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2ejvazkev.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gt2mnmnizgx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2enoqpbnc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gt2qudjqvmv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfvuhqyx.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqiwjsr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2tebxnilc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gt2daxylwnw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2gshsxelv.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2rtabodap.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2wqporzye.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihewwgiy.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2soagfwyy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gt2fanrkjbo.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gt2smkbinqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2fhsykwyp.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mecfzels.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2usavzclg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2fwefkjvg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tkuidzle.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2ykpjjjgy.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ilvottii.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2nalztckw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2rjnfqadi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dkfdrqet.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2llokpxzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sqqhnsob.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wgsthqcu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qarbyeva.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2matmupzq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2totnusyk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2dnoahjgb.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gt2uxmpdbey.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2dnssowvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2ehkczgzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sciyomnq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2matasxkj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2ikqhdjro.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2mllzxanv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2lwatgabr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdqlueqc.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2svtzrctu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2hqgowanx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2jwihebkn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gt2ityinwvt.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2qdeblxsa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gt2dsjmjbam.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gt2eqsmoenl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2jqclctor.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gt2lebkagtg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2reoahpgl.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bitssfcl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bitnojwj.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2ogyqwanb.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2edhcebgl.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zdekszzr.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdwwycap.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2dferftwe.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gt2xusnoxpa.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2behwtepi.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2fafedvdk.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtdokabc.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2hksnziox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gt2pksngaql.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2kxfkrppq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2oydfmbbr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhwknak.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2xarewkah.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ciogjucq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2efojwbrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2bgkbjbku.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gt2fmifwbut.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaqggait.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2sionubjw.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhlnvmet.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gt2ckhjnnjf.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2gbzjzubd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gt2fwngnyos.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2nyihkvln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2qgifmuwl.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2wezxjdig.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpjpepkm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2gadwmwau.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2rtycmodg.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2gapyyefj.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2ploagfbp.html


<!-- 参考信息 -->