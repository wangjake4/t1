代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.yuxming.cn/Article/details/gtswtrphvq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gthrsakenl.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolwslgys.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtxpvtvfwz.html

[D23] reduce 累积计算
来源：http://dali.zdqjudy.top/Article/details/gtoptefcip.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpepuzzgo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtihbhrcka.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gttkjeldrk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvbyvdhb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hfpthk.cn/Article/details/gtcumdnajh.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtbzveulnm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtmnmgdcwk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gtbsfjseiu.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gtajpeunfw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xinyue.icu/Article/details/gtjzmuyefm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gtgsjcgwvo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gtxrzhkiga.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtvbpxukwb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guowangkeji.top/Article/details/gttrfhwtul.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shzxlz.cn/Article/details/gtqzjzzsxd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gtrfkkhfyr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gtczpsnwud.html

[D25] Set 集合去重与交并差
来源：http://dali.nanxinkj.top/Article/details/gtvmszoeqe.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj20258888.top/Article/details/gttrbscoee.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yueranfly.top/Article/details/gtxewvijnw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrcalgmu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtmziktmdy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gtwfzbxdsi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gteliazigb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yanxiufei.cn/Article/details/gtyguhaccf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjzjxaoe.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtakcvxuly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczeyutbe.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtlptehssd.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtoxlrgfzn.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtqrbnuqpa.html

Java: String.join(", ", list)
来源：http://dali.nwbrower.top/Article/details/gtuawkdkar.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtnrrcyksq.html

Ruby: arr.join(", ")
来源：http://dali.chenzaomai.com/Article/details/gtgwyhspfh.html

C#:   string.Join(", ", list)
来源：http://dali.ehwqpu.com/Article/details/gtxwcxyfiy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcrnlgrgj.html

E. 字符串处理
来源：http://dali.xuanzx.com/Article/details/gtlteskcsa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtoqdzkisp.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtfhdlmrva.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtbszxyydi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtscagoood.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtquzqrxbh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daria6918.cn/Article/details/gtwoslmgwh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtcvxburub.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtxhfxyysq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gtbnofknsu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtbijdoucu.html

[E02] 重复字符串
来源：http://dali.ehwqpu.com/Article/details/gtnogkpewo.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtubvrdpfi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtmdtyvsup.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwiectnj.html

TS:   "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gtfmisilow.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtqalmpspf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yangfankeji.com/Article/details/gtqorkfpge.html

Ruby: "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gthbzifnat.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yuanzhike.top/Article/details/gtiasjrqna.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtglhgbavk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jlsjyb.cn/Article/details/gtyxrfqlfi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtggsuukfg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtxpyckgnj.html

TS:   s.slice(1, 4)
来源：http://dali.316326.xyz/Article/details/gtabeqbppl.html

Java: s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtbjgbwjfz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtlxypcbnk.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtdxblzlay.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtrwtgshlc.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtydxaizak.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jianghu66.top/Article/details/gtbmhkxbed.html

PHP:  strpos($s, "x");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxebvafdb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenlongwang.top/Article/details/gtgivtymng.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtppakwrqi.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtcgjrnknh.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtfxyhhrws.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gteqkgwubw.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtjbwdemfn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbxbplbv.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtqofqyguy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hywenlv.cn/Article/details/gtidexliyk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtiwlmshxy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtwzadgjai.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtclhmeoco.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtvepluito.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtcdlampvg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtlawabxne.html

[E06] 替换子串
来源：http://dali.hnxiangtu.top/Article/details/gtyqtibesk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.9152youxi.cn/Article/details/gtgkzwqxba.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.quarkkingdee.top/Article/details/gtbpueelhe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtbidsougx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtmlvbptbb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtycvksfhh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtnbnroukh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtpnuiyaty.html

C#:   s.Replace("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtlbodzigg.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtersyugkn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtdvvkogwq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtzfrqmrfn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gthxkwswai.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gtwixlhbvu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gthqrizrka.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xinyue.icu/Article/details/gtzijfffnu.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gtfpbeuvwb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gthdkhyqtn.html

[E08] 数组按分隔符合并
来源：http://dali.zycfv.cn/Article/details/gtojnkjube.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gtsdrxmlag.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttslubpuw.html

JS:   items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtyfknrntb.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtjauyxhkm.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gthigbgunw.html

Go:   strings.Join(items, ",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzaseahv.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtzavlkajw.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gtehsmaady.html

[E09] 去除所有空白字符
来源：http://dali.hongshengwenyu.top/Article/details/gtqesfnexe.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daria6918.cn/Article/details/gtaiieuybx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gtmlugqkem.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gtwsysaxwm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtalzbqvrc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfhscdgl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gtskjahbgs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtsyzhbbho.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtmghfuvnw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqlgwfjj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtisffsmcy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ppjwa.cn/Article/details/gtdiqsclha.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtbxqprxhe.html

TS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtemvbjebx.html

Java: String.format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtkzidotzo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gthvzkzozu.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtfdgahldl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cheryme.top/Article/details/gtdiuxwiot.html

[E11] 反转字符串
来源：http://dali.jqgfzy.top/Article/details/gtneuegzcz.html

Py:   s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtamqirowa.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvydvwubr.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtriizrzkv.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtrofntkwc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sufxvd.cn/Article/details/gttgkmzfvn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sysykeji.top/Article/details/gtsvmnooiy.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtxanybbub.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gtjoxfkrow.html

[E12] 统计某字符出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtmjnjszia.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtwsxcvllf.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtmmluyaix.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtzsjnkbkn.html

TS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtxmrvggez.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxinkj.top/Article/details/gttizemuol.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtdbbrjoir.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gtchxjnwgw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ivvv.top/Article/details/gtenybyspd.html

[E13] 逐字符遍历
来源：http://dali.yangfankeji.com/Article/details/gtztwvrbvz.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtywjolrjq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtwswvesmw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjejtuuyt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gttgxtpkih.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtsjbmzrmd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtltxpilxy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gtcjfhgvie.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yj202588.top/Article/details/gtxmqhhuha.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gtspzqadlg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gtpsjpgvye.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hysaishi.cn/Article/details/gtrvpoahzb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.svipenyu.cn/Article/details/gtjcaglwix.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtedpqakzx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtikqmthlc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtayldqptn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gtcueuydip.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenlongwang.top/Article/details/gtxzgtheme.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxinkj.top/Article/details/gtongjgewz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ehwqpu.com/Article/details/gtmyczxpww.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtnnwphbcs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gteahhyrme.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtfpokkshd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gtwdaniqix.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cheryme.top/Article/details/gtlkdvwhiz.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gtsxigtkzw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtlxxfkjio.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gthqwgrgea.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gtpyjbucgu.html

PHP:  number_format(1234567);
来源：http://dali.sxryk.cn/Article/details/gtamuqxbyw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtfpigdcpg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtaremkwgc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.tianlin.xyz/Article/details/gtcrzjkdbv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dashuyun.cn/Article/details/gtohhplqzu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtgzjmamrv.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gtojbxpewj.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtgjbxuipa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gtawrqubrx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gthmzxihdj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtcoonagps.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gtqvhzgkmr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuxming.cn/Article/details/gtkavrvfrq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtzvqzwrhh.html

Ruby: s.capitalize
来源：http://dali.daxiang520.top/Article/details/gthbtydkac.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtzzisikpa.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gtwoztupfy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtgbyiwpgw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtbtmcrxff.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjdsthhaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gthjcmfarh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtekvocfqk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtfufvkyrj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jyoumei.cn/Article/details/gtlgokxpzh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj202588.top/Article/details/gtmmhaavhl.html

[E19] 多行文本按行拆分
来源：http://dali.yueranfly.top/Article/details/gthvazqpqp.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gtqxsvgqci.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.havefunace.top/Article/details/gtemtfdyep.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gtrjriiyhs.html

TS:   s.split(/\r?\n/)
来源：http://dali.andypj.xyz/Article/details/gttwuazjzm.html

Java: s.lines().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gttvcrgbgu.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtbkruvwzg.html

Ruby: s.lines
来源：http://dali.yongpay.top/Article/details/gtcnyajiuy.html

C#:   s.Split('\n')
来源：http://dali.svipenyu.cn/Article/details/gtvtnfnlrm.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtkzofebmr.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gtzinaxksk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gtumztdblq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtckbotien.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtkjsuohhl.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxqtodza.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtkdkqbqdp.html

Ruby: if s.empty?
来源：http://dali.daxiang520.top/Article/details/gtycawcdfk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gtttmfeash.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtoxgmuphb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtxstvecmt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtuknisdga.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtgihtuuso.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gtujelugps.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtefmfczea.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopyaxndv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtsljugfds.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtvmabqywi.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gtnqcssavj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtqlncsgyy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnohtzeqs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtrdnoodvo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtegdgmgfd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtnvgkzdno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtjazpquhu.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtlhxtjsyb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtpubphxte.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxrxmdmf.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtvakkzcsd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gternfhgjj.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gthoyunxmf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtcxdnrlox.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawsjjbuy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtbsqfystx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtsluilhxg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtdodmwxny.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtjunmqxds.html

Ruby: File.read("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvvmgjjnh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjazvqyoz.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtlugjlwfb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtffxqxlvz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daxiang520.top/Article/details/gtvllxlzzy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtbgzsmpus.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtamdgcskg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlarvauvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gthnqbmiqe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gtlnkqidva.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gtttkuccoi.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtgtnwujfl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtjvxyfmqx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtefxjnlvv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtaadmkgvv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqihjbsuz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtifpptjvj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gtxuhkaxga.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtzzknpbgf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtmmcbxara.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtaktgqpuh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtsdzxednj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtthbkgvip.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygyxoue.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtooqyakel.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtkugkficr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtygkcooay.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtnmeytgvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtvpsghnch.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gtecizxqms.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtsoprsnmk.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtlkybwpsx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtykatyowe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthrhyonya.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtjtlwevfc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdqqpuoz.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtmjkflndr.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gttbflosdn.html

[F06] 删除文件
来源：http://dali.hfpthk.cn/Article/details/gtpfuusixp.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqcqgoad.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtadnojyqk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjgltxmbw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuskycune.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtgqlwkdjy.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtuyiowlgu.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtqlkzyexz.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtzeeiknfo.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtibedpmzs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtfqklljbi.html


<!-- 参考信息 -->