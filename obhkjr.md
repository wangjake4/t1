代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtuxvlydar.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjcxmsyl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtuvhzrfkv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtdztgqcqi.html

[E06] 替换子串
来源：http://dali.cucudq.cn/Article/details/gttttdwhpk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtjybnxort.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ybcxt.top/Article/details/gtcdsajrbs.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtiosqxqmh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtfqsbhxvx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtsjgbfvww.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gthmctaiev.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtdxmkorjh.html

C#:   s.Replace("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtpidbzlkb.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gtecprbsvi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gttaycfewf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtqwnoqyea.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtooijvmqk.html

TS:   s.split(",")
来源：http://dali.yj20258.top/Article/details/gtfrgbwgvq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tian-w.cn/Article/details/gtyvukxych.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tian-w.cn/Article/details/gtgzebqskj.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtbsnwjqbu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.feifeiyinyue.top/Article/details/gtqvlojccz.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gtnxbxfkey.html

Py:   ",".join(items)
来源：http://dali.wangshuangyany.cn/Article/details/gtobctvvmy.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gtfdygznfu.html

JS:   items.join(",")
来源：http://dali.guannengcc.top/Article/details/gtslbnjiia.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gtzezyfmey.html

Java: String.join(",", items)
来源：http://dali.yj202588.top/Article/details/gthfwknlnx.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtvrnboyyq.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gteaisuvxg.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtejugqmfq.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtqnsrdsma.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.birdmap.top/Article/details/gtezominql.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhengqikj.top/Article/details/gtrsgifjzz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtdxwaxoow.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.gaohongyu789.top/Article/details/gtmywokctd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jianghu66.top/Article/details/gtasdvvsje.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtynovvscm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangdashe.top/Article/details/gtjcmipeug.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtokwjyiug.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gaohongyu789.top/Article/details/gtkigexdvn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtncgucntm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtehaqbvho.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtpeotevpl.html

TS:   "7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtqjwoouqv.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtiopjvcbl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gtcvcgcrye.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gtrrqwcpqi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ivvv.top/Article/details/gtsmtbjbai.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtwifqorkf.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtexptukzm.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtgkybtktk.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtqppisxhs.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gteijwyyrv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtuvuqwyhi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cheryme.top/Article/details/gtmljqxmon.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrpxzykn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtvbjopzjz.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtrpnuzfgu.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtidbobdnp.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gtdxcqeapi.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtrfxuxsvi.html

TS:   s.split("a").length - 1
来源：http://dali.ivvv.top/Article/details/gtqhvhlofh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shzxlz.cn/Article/details/gtguypnkte.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gtvjzetjwg.html

Ruby: s.count("a")
来源：http://dali.yonumen.top/Article/details/gtgkamniec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzddgeuw.html

[E13] 逐字符遍历
来源：http://dali.quarkkingdee.top/Article/details/gtovilgrvr.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gtdojxfafa.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteposqjlo.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtgsaajezw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ybcxt.top/Article/details/gtmtvzuqrg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yuxming.cn/Article/details/gtbfgzkael.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwldhteej.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhijiandao.cn/Article/details/gtyqqhfynd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtnejntort.html

[E14] URL 编码与 Base64
来源：http://dali.jqgufenzy.top/Article/details/gtwfpmavym.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtmltqgwpf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gtlucrtsdv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtvuzniqkb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shuidangran.top/Article/details/gthefrwgii.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtxcqzfgmd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gtujvvegez.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdrqxumk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtsbcjupqi.html

[E15] HTML 转义 / 反转义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtsicjwj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gtpjyzbont.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtrldjsahk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cqqwz.cn/Article/details/gtsczwhcnh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtiavkzckp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gtxfpmgekr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtsobszdiu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtcutqdunv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.fengsongda.top/Article/details/gtbpylzoyq.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtwhboechm.html

Py:   f"{1234567:,}"
来源：http://dali.zdqjudy.top/Article/details/gtwcgeoupp.html

PHP:  number_format(1234567);
来源：http://dali.chenzaomai.com/Article/details/gtyngfrjih.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtiaanyeeh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtyuwgnyjf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zdqjudy.top/Article/details/gtkcjfhdxh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.c1oappe.top/Article/details/gtewnmeegy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gtvykwrjzf.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtjtwtpakz.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gthdbtrxrw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtdtviglmg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sysykeji.top/Article/details/gtguyxaqdg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtjskbfxuz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gtqiakzomc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtnkziorml.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gttojklyel.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gtnnsvpnhf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gteqjenqov.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtpjrexyev.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gthdqjwqtf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gtewnfwsan.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtppoydziz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtkmvwsjxd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtleqkxvlc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtntjwdzzv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtagddpryk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtndipxpcj.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtxpsriobg.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gttvfxglrv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtqdwrhxcf.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtvpzlwhkz.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztsbwrgc.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gtshksaria.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtduiqajxk.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gttiaxswsf.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtyqdwdlqo.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gtgrkdgnqs.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gtozyqgyqn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gthdnfhlua.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtoxbixisf.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtjbrhibtq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrltkmild.html

Go:   if s == "" {}
来源：http://dali.hnxiangtu.top/Article/details/gtckeyutfe.html

Ruby: if s.empty?
来源：http://dali.feifeiyinyue.top/Article/details/gtbncfskao.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sufxvd.cn/Article/details/gtgqiytywj.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtcjdzqhdr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cucudq.cn/Article/details/gtuzicbhwb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtedjaakkt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtmqulqnbw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfhdbfkc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtmalbkbru.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aibaodan.cn/Article/details/gtaqxakgdl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtaplzjllc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtpruhagzr.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtpbmpvftw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtimqfqzln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtkbjzbdbh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtitfylaqx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtpxuzprfa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtqyfieicn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hongshengwenyu.top/Article/details/gtuqamovex.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtyrdjqkid.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cashguo.top/Article/details/gtvuvrrwjm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtblsxdpel.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtayddhdpf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrqzfbnoq.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtamwmbfjc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtafjnkwlt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjbozcevn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtzwavmwxm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtubsthivv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtlgqmxwta.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitpvdqrz.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtdimalmpl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdauasssn.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gtnpwcxlif.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtrtcqmuub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gtuwndewoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtcwysgnua.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtkueaxofo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gtowczbraf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtynwignen.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gtdwbkekod.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cashguo.top/Article/details/gthldgdbkp.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtdtebkzxb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtaeskhkcw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtvoepaysw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtzrlxtold.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtkagldnea.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gtexxlfini.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gtzyqlcvrc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gthrusksbe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtacznvola.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmaqhkudo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtjdsdznyo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtiqtwegvp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtqzbvypvp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtwnrypqxj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtqrewgbwe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtvnairliy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtljhyatss.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtswjogfdz.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtytmovjjh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gtwbfkhrss.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtsolgtyrk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqkiyhxao.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtpdwgfaew.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtcmdmyenr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtnaikmfkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdgybkhbr.html

C#:   File.Exists("a.txt")
来源：http://dali.yonumen.top/Article/details/gtodooihrk.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gthervzgiz.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnmjmvhmg.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaptcaas.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbslgrwnx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbehyaurn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtxbwfcntn.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtnhmkhyrq.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwjpmocqt.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqvhohifq.html

[F07] 创建目录（含多级）
来源：http://dali.ivvv.top/Article/details/gtyuubbcjo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtkfgjlicg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtmudfoghp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gttbgxrrsb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtocedxura.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gthkenfffq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.c1oappe.top/Article/details/gtruonwyam.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gtqqncevus.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtkwcoipzi.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtvquacvzm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gttlmzzpbv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtlixyopwn.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtwoaxqtht.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gthmrnnkae.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtpwveoxif.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtmcdbyfjx.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtdxcwinth.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtufrmdbjj.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gthfjolqwc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbufoxrbz.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtlyrrwzpy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gtbxxjqufr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtphqgltdl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtemcdyijh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtqoqwonij.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtyazikgxo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtytnpbeap.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtncmorsqv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrqnctsyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtbcpdwyhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtaemoyuab.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtvpcebzus.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqfyjogx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtyqwcibkc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmbbwugfl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnvhevkif.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtefnlhbio.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtoghaohoa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtwpgryyjb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjyexeszf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtcflpodli.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtkvvdgmus.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtofgtwmey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtmaurceha.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtaudielkw.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtvqntghqr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtmlbtlhhu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtlhbjnemu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtrfogmjrr.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtrfvfusgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtmqynbvhx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gtrwuasdby.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gthmlctvwe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtcdwxmdyj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthwhmqwtk.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtbleaempk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqjbvuiof.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gttltdxnos.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtykjtncfa.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gtnpynqggo.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtfymgwgty.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtizlkoenx.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtadcnzedx.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtmxbrydyv.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gterzmjkst.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtintwcswn.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtyxrgrbha.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtlyxphtsv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtwjmkoyup.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtfpwoucny.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtrqalagmc.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtalgucyzy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gteesbzglj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtztmzajpc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoquofnxa.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtriauueql.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtmyafihre.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtgwcwtewg.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqgkxhvf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtwebrnaux.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtohuzdyet.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtlgrhnyep.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtoobncmbb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtxigwvvsh.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtplcmtpba.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqqwosjo.html


<!-- 参考信息 -->