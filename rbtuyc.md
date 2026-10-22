代发 wailian999

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtmunzcyfu.html

Ruby: arr.include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtqlbkdlfx.html

C#:   list.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtnlpnxsew.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sysykeji.top/Article/details/gtmevvrwqi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cdnleiting.top/Article/details/gtphvjvxvv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtuarxwn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtattdgmmn.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtqkwejnjo.html

Java: new ArrayList<>(list);
来源：http://dali.kuanghao11.cn/Article/details/gthguwqthb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtbnalpjnr.html

Ruby: arr.dup;  arr.clone
来源：http://dali.smart0.xyz/Article/details/gtfznljcgs.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtqtcomhgk.html

[D23] reduce 累积计算
来源：http://dali.zhongyouzk.top/Article/details/gtfdpxqiky.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ehwqpu.com/Article/details/gtexwmousg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zycfv.cn/Article/details/gtaivhrlfc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtphtusujb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.0kj1m.cn/Article/details/gtspwfpzxg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtkeesktbb.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gtpmejxwhm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gtkgjtuzml.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtiyffcwke.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gtiqxitpqf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtqijbrpur.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zycfv.cn/Article/details/gtohghhztj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtppqxzdew.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.316326.xyz/Article/details/gtqvdfdily.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gttkvmkvow.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jqgufenzy.top/Article/details/gtyflfvhbn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtybsjmfvl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xylfe.cn/Article/details/gtfomrwdrm.html

[D25] Set 集合去重与交并差
来源：http://dali.ehwqpu.com/Article/details/gtvithujsx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtymvwieqw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtllpsiwpx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xuanzx.com/Article/details/gtlsxulday.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.iojbl.cn/Article/details/gtnbylzkep.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj20258.top/Article/details/gtavcejzpi.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gtolrbjefu.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gtaxynltcl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj202588.top/Article/details/gtnchvxnrt.html

[D26] 数组转字符串
来源：http://dali.ppjwa.cn/Article/details/gtzsbnuebb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtjsouvgbn.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzoqblooh.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gtwntirqsl.html

TS:   arr.join(", ")
来源：http://dali.ybcxt.top/Article/details/gtxlkwlvby.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtmgenkuex.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtxhrmfypn.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdwdwodm.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gthectiagt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtayfgxfkd.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtstfdjmfy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypxtfyef.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gthgnaiihy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtidgixqet.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwewomyu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtgrsrsgkl.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtlljamint.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gttvhieuzk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shzxlz.cn/Article/details/gtnmmivyfk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckmniusx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258.top/Article/details/gtmhgrxkhp.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gtyqazkloz.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtdsnhessc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.mhx1999.top/Article/details/gttyrgxtto.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhkdqivi.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtkldrxnqc.html

Java: "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtsvziacqt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtebsemvlu.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtybtayfpw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtopmnjlef.html

[E03] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtpuknlnif.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guowangkeji.top/Article/details/gtoklvrukf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtycsphbhd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtrynpkmkx.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwqzyjjp.html

Java: s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtbdqldyoq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gticbjynem.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtujbotivz.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtsahucouh.html

[E04] 查找子串位置
来源：http://dali.chenlongwang.top/Article/details/gtjncyvlpv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtcdifuepy.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtfdrsaxcg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtmhlisxrj.html

TS:   s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtfltbaykg.html

Java: s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gthoqeyloc.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtttgycqrk.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtsawkclfa.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtrcirvoov.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.redwolf501.top/Article/details/gtwwfnbjut.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnurojwuv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shzxlz.cn/Article/details/gterubmgfn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoaxkayv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtrqscgduz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gthjyiloeu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shangyingyoupin.top/Article/details/gtcfmcepya.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gteeoylyqn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtzqfnplbk.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gtzlysmppa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ybcxt.top/Article/details/gteqxoxoxy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmdevvmw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtxfkvdtne.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtjswuaanw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtwxmqdopw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvsboyyo.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtktqtgtzk.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtukovgqbv.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gtdsugzogh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gtmqkgomqq.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtryxwyxar.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sysykeji.top/Article/details/gtkhnsrurp.html

TS:   s.split(",")
来源：http://dali.jlsjyb.cn/Article/details/gtaweppqye.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yvedp.cn/Article/details/gtbuixrfuk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gzhubu.top/Article/details/gtdwqxamaw.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gterqcswrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gtnbfiefzr.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gthsivzvzo.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtpshbakns.html

PHP:  implode(",", $items);
来源：http://dali.feifeiyinyue.top/Article/details/gtxrrkklmc.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtfkqajove.html

TS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gtwotpjyzm.html

Java: String.join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtawxywocd.html

Go:   strings.Join(items, ",")
来源：http://dali.aibaodan.cn/Article/details/gtmjqntdhx.html

Ruby: items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtqilemtgv.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtezpxzcvc.html

[E09] 去除所有空白字符
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjezgketc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiroiviik.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zdqjudy.top/Article/details/gtxdxvpnml.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtaovnaali.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtwbqivdhb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gtzsleirnt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtqcmwrcex.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gthbrjhtio.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtxvclwsml.html

[E10] 左侧补零 / 定长填充
来源：http://dali.mhx1999.top/Article/details/gtqffzkgin.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtevghiznp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258888.top/Article/details/gtkuqqdwlx.html

JS:   "7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtqlphdkne.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtrueyswzi.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtqmzwubht.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtkwbqmbvi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtdsattfsi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gtjnkncvks.html

[E11] 反转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtreteohjk.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gthaowsbyl.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtemzypkkg.html

JS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtzvkkdatv.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtqewoctba.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtgvunyzfw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtgtodvtrk.html

Ruby: s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtoeqkjcuy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtpzbjqfrp.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtnpztllrp.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtuqldhfio.html

PHP:  substr_count($s, "a");
来源：http://dali.yj20258888.top/Article/details/gtekdzigrc.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtgolsezml.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gtyywbialc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sweek.top/Article/details/gtgwgyweoe.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtebgvbrfj.html

Ruby: s.count("a")
来源：http://dali.smart0.xyz/Article/details/gtgusyzopi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xuanzx.com/Article/details/gtxynlcgwl.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtcopkklic.html

Py:   for ch in s: print(ch)
来源：http://dali.yvedp.cn/Article/details/gtbbrardar.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtjgjskqhx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtjdbwjrbg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tanke756.top/Article/details/gtvgacunxq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtxpnlzacq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtozkiiaxi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinqigufen.top/Article/details/gtuqxvllec.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cheryme.top/Article/details/gtosusknoa.html

[E14] URL 编码与 Base64
来源：http://dali.vqdsnc.cn/Article/details/gtwaettikk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtcomwmkdy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gthhtsgiuh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtymhilrdy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gttocfrdbc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtgfbsjcfe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtadnswnlz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hammf.cn/Article/details/gtpsnjthjp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqkoorwr.html

[E15] HTML 转义 / 反转义
来源：http://dali.xinyue.icu/Article/details/gtrnnlqrut.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtbznskeai.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtozmteoeo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gtonubpeus.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtshohezlc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtbuspksrc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtnldxyixn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtjklxowpg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.iojbl.cn/Article/details/gtxngkkauw.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gtwmqkgqjf.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtplwmzybn.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtbyxeyfdb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gtqtxmjktu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtyezwtinl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtvivflues.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xinyue.icu/Article/details/gtyatgzthl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gtftwvpmjs.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gtynybfwsv.html

[E17] 首字母大写
来源：http://dali.sxryk.cn/Article/details/gtldqnekze.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtywgpovab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtfstgzbxu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gtkalaodiw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxudfrtcq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jqgfzy.top/Article/details/gtfqykwibf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gteyxkwkjk.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtlyzjgjig.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtfkkrxgmf.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtxdtottlx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtfhwderpu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gtpbnxvaiy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gtawlzodjr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtencgqwcg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtdgfpyrua.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtpaduyaxx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gtpxkvyzvs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtwgpzsx.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gtpwhtwczn.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gthjzlimlx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtgqgvynvo.html

JS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtbsfbuklg.html

TS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtygfeurls.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtvnoclpzw.html

Go:   strings.Split(s, "\n")
来源：http://dali.aizwys.cn/Article/details/gtfvljzhlh.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gthkjftbhm.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gtthealbyf.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtofefayae.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppqjxyzo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gtvaspxgay.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtprgvrtyw.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtxklgrfdq.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gthsrpigeq.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gtvtxwbuyl.html

Ruby: if s.empty?
来源：http://dali.zhoulong.xyz/Article/details/gtntnfyyzd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gtkihnauqx.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtuvaahkwu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.havefunace.top/Article/details/gtgygluvzf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtodkzrvmk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtpaaigece.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtnwpqewnu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtvxupygdv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gtqrsxnsqa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtnchuyoft.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gttvwshihq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtbxbtogpz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.meibo888.top/Article/details/gtoodxfekw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtrsrxwuqw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtmlemofie.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtphuzpkbs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gtdqnpleiu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtupesbeca.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gttwcsihdb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtpxsnocmv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzwwpvwnj.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtfgmkcvpm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtobiiwiza.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtfgnqgdhd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtetawhvkx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqonprwc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gtkngvispe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtwpyscmig.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtdkanfxts.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gtggwdnlah.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtznrcwiol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtuatanirm.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gtsysxllcj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtyetnaiir.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gtruscehpa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtcwjgkrvk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjrvkercd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtogcktfvu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrudmkrg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtfxzekdcq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtuxdaxcet.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtnbwliiyt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtnwggzfvg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtujopslzo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtlpxaqgej.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtlmyvejvu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gtvsssygbh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gtvqmzmwsp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtawnysbaj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtlwkpoaob.html

[F04] 追加写入文件
来源：http://dali.dashuyun.cn/Article/details/gtvhjkvqjh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtlofztuuj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtfskqgmmc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtzdxfzbry.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtarqstija.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtxjwymzlm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtchsevfhq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gtjocpgfxh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtvndbnmzx.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtrfbxbxwg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtbmjehijf.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtwbdjocfk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gttdsvhqif.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmlkspydb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwxozbuu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtmyrnekyu.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbovyrypp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtabarnpgp.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtzpyzzndz.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvrybltmw.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqcjprvet.html


<!-- 参考信息 -->