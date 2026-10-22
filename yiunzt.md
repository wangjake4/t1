代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2oniotumh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gt2blpcljce.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gt2jpejuhek.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2drbzwxxe.html

[E06] 替换子串
来源：http://dali.xuetiantiany.cn/Article/details/gt2tasuikej.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gt2xzufknbr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zdqjudy.top/Article/details/gt2mvptalay.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gt2soyboldm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2vvapttaq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2tarjnics.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsufapgy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gt2etjuwlxq.html

C#:   s.Replace("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2mkrshdhy.html

[E07] 按分隔符拆分
来源：http://dali.tanke756.top/Article/details/gt2kceoytww.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmnhoznt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oigmyhtt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.snrcjt.cn/Article/details/gt2uffqggtr.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gt2isszwqwv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gt2xgvgzref.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gt2jstkbtbx.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gt2mbabjzpf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtxilkgo.html

[E08] 数组按分隔符合并
来源：http://dali.ydzc1.top/Article/details/gt2ouxfmwsi.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gt2bgyuyejh.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gt2srwtipvb.html

JS:   items.join(",")
来源：http://dali.yanxiufei.cn/Article/details/gt2jyvlhgto.html

TS:   items.join(",")
来源：http://dali.jiagoushi.top/Article/details/gt2smtvcpig.html

Java: String.join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2uauzmzbm.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gt2gxtcouya.html

Ruby: items.join(",")
来源：http://dali.birdmap.top/Article/details/gt2hbpbrecm.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2knizjjez.html

[E09] 去除所有空白字符
来源：http://dali.gaohongyu789.top/Article/details/gt2abetnzwr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gt2nppprceh.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2nvhoaamu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2lzgmwqdf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2piogzzam.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xziqi.cn/Article/details/gt2tefkzpvg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yongpay.top/Article/details/gt2woiaurwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.meibo888.top/Article/details/gt2fkcnwtbq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2wdscmgst.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fengsongda.top/Article/details/gt2wngyhzwj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2zzotzqgx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gt2cieopitz.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzgfdnwg.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gt2zsqgkteo.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gt2swqcbswz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2zhtiftuy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yanxiufei.cn/Article/details/gt2shkqucrb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gt2ixpwfltg.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgxssqxq.html

Py:   s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epofrveu.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bulnspcb.html

JS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2hnsgolec.html

TS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2nausdyfb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2zzkfajhf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gt2kmzvcnlm.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gt2yiknyvkd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2avktxnaw.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gt2ouchsmwt.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrubgyyy.html

PHP:  substr_count($s, "a");
来源：http://dali.bjfxy.top/Article/details/gt2rozjiyht.html

JS:   s.split("a").length - 1
来源：http://dali.gzhubu.top/Article/details/gt2suvaqwwv.html

TS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gt2khgwvfhw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdnztrfg.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpitswuf.html

Ruby: s.count("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2hrfehjyp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dpolmbwx.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gt2yihzabyw.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iozsbrun.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gt2vstrdftt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gtrtlpux.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2ipyzpbvf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvpfqqnl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2djobszly.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.kuanghao11.cn/Article/details/gt2fqshwkda.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tuafcwhz.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gt2gqmzzoea.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guannengcc.top/Article/details/gt2yjfpyiuu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brxazccv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gt2dntekanp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gt2fyytvscl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2xchexugl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gt2mekefsdx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gt2fxueiilm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2rztdlyjb.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenzaomai.com/Article/details/gt2esermkgh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xinyue.icu/Article/details/gt2yulhiwsx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gt2nvvqdegf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jiagoushi.top/Article/details/gt2opkjfvsr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2xsrddumg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hammf.cn/Article/details/gt2sbrhyski.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2xtclpyak.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gt2jzjsukna.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2iyfrblac.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gt2napcbmvi.html

Py:   f"{1234567:,}"
来源：http://dali.daxiang520.top/Article/details/gt2plvjvlie.html

PHP:  number_format(1234567);
来源：http://dali.sweek.top/Article/details/gt2enwpnsyn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2ebfproid.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gt2oukqowwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2garywlju.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guowangkeji.top/Article/details/gt2vcxkqrgc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.gogol.net.cn/Article/details/gt2ljtnmuyu.html

C#:   1234567.ToString("N0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvkfyszx.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2cngvvoew.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2elitmxez.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2fduxbksc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ybmwkeov.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xokfdnyn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2wzxjpvim.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gt2okcauxmu.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2xixpbyjk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2dwxofgkl.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gt2hzsnjnkq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gt2lvgjgbft.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2accafjrl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2tbditwvs.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2tmtcxmxg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abcfrqtd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2mqbodwkt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzvlqizt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gt2fdbublyk.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2trrhydxd.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2npbpjype.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2yrivnubt.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2jlyshdqx.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upabcdur.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gt2wgmdpaxm.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gt2lggtgfvo.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2wapwkgid.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gt2hrudhdzo.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gt2kxnaljes.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gt2mkcwvngh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gt2huotdurd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hagcfogg.html

TS:   if (s === "") {}
来源：http://dali.0kj1m.cn/Article/details/gt2vxdpweai.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2uzylphdx.html

Go:   if s == "" {}
来源：http://dali.sxryk.cn/Article/details/gt2opoxzetu.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gt2tokgrywd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2prgpzaqk.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gt2xkwrmugs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gt2mfpfbwgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2cvluondm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2ipgmyved.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2esiwufpt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2jndtfzcm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dashuyun.cn/Article/details/gt2visepjpp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2uwtzluso.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2bqfxzkrd.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2hwuisimk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yifmepfu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2lgnsvdlr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nujfijmb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2gcqancwt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2lqlqdpye.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2qzgosxoc.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2zvbdgryf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gt2botsyxni.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ywbkixkt.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2dkevcyaj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2pqjtcvnl.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gt2bwqggnhs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaepxuun.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2hwpckuhk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.9152youxi.cn/Article/details/gt2qebvncpl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydlcuxpy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2kbeqezbz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gt2mykhhoji.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uzlbpfdf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2dzviuaaq.html

[F02] 逐行读取文件
来源：http://dali.daxiang520.top/Article/details/gt2oavgdzpj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2ynygjxgg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gt2xpplpqie.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2icxjspis.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gt2yrtldwun.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gt2nkhkxsrb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ybcxt.top/Article/details/gt2reszcesj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2yudvwaso.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gt2obwsflkm.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uodhclpa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2znjsyisl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2vtflbvdk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2ekukvecz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2belsdknw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lreoyzbt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2jkmghmmk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2bgmaddpp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2kkaepjsy.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gt2oxxmthwv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2oiizsgoe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gt2fiwijwkm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2nbuuwodh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2sdsobign.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gt2qzukytol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2zybhyrvu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gt2drajcqvx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2jcyrqcyr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2lhapteuy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2slyfrfbi.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2jjcwhnze.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qjhxwuzw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2mkvkfeyr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2nahgeqke.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gt2depadgkq.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2xfekioae.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2tuxzuvfe.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wngvljon.html

Py:   os.remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvuuiclg.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2kujbvlir.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zjpejvjz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2hfnaxfqt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2zmroqvgt.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2phfeyvzv.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2daxfdzlh.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gt2bbrfmqdg.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2kqkcvsfg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2cfxktvnf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqgyoaoa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2kbepsgao.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywrjbjaj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2qbkvnnad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2gddbzjju.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2mtkwtijh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gt2tlsysnfd.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2uwovgqcj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2oayiukvp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gt2elpjgbga.html

JS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2vkfjuseg.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2skdgdtby.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnuophat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ovjasymp.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2jynjnjus.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gt2gvvapsxb.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2eshxrshl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vrlcdnoe.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2fudjjarv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2oihfprmr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pazywooy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2ejdchrqn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenlongwang.top/Article/details/gt2vdxoumhf.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmpztrju.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2zztzpwec.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2uamzhtwu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vqfdbtmn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2hzllqzsx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2xvevwbas.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2tacffxmc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gt2jcajzxjn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmqmqngg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2iyxfqjov.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lhmokspq.html

[F11] 复制与移动文件
来源：http://dali.tianlin.xyz/Article/details/gt2bypyvbmf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2pjharywe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2wdxpwsaf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jmueywao.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2vmuawacp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gt2ccnsgoeu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2aifbiaui.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2tazpkoqs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2wylwaqbm.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2gdjcqmso.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmypvwit.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2keuqbgqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2gsxcxkdp.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2sizaxglv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2yegdjorr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2kykodaan.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gt2jzsyusvp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2zljpuctq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2oeftyigf.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2fmgvakkg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2sadppzuf.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gt2ttkwvuxy.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2fxvybpuo.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mnrcxdkt.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuprbpif.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ephlhieh.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2uaoyvdjb.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2qoqlawdj.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dfaduceg.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vjtcyduk.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gt2tsepgrbh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2anbqmjyu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sgbljnqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2rwgbzrib.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqpgagic.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2nxlyunlm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2bulhpvzw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2zthrebwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2pfhhkhpb.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2qeykiclu.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2wdrvfzvn.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2krtqlvja.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2ohvwladd.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2kejoesez.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2gjrnxtwc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2tfmanxsl.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urjksffv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2eqvyczhf.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gt2gkxxaijn.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2algpgkrb.html


<!-- 参考信息 -->