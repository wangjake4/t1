代发 wailian999

Ruby: arr.tally
来源：http://dali.redwolf501.top/Article/details/gthhadwawo.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtebhtuqws.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gtwrsevolx.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtoelawvmz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtrkfwelet.html

JS:   arr.includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtxbipkewp.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtukqndaor.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gtipgncoag.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtzbnxzfgv.html

Ruby: arr.include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtogmqambh.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztqddjrc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkovcdrn.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtonjzgluj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hywenlv.cn/Article/details/gtjfrbcwhh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtivymdrhq.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtbvkwpmxg.html

Java: new ArrayList<>(list);
来源：http://dali.haohaochexian.top/Article/details/gtrnayxcps.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtyzpidmzo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtdbkczkxx.html

C#:   new List<int>(list);
来源：http://dali.hnxiangtu.top/Article/details/gtqtjtdder.html

[D23] reduce 累积计算
来源：http://dali.jqgfzy.top/Article/details/gtlytntcwn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tanke756.top/Article/details/gttzyqcmcf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tanke756.top/Article/details/gtjbdwhffq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.nanxinkj.top/Article/details/gtofvonfkb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daria6918.cn/Article/details/gtukjmjhvm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gtjcmeejrl.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtxmwuktbd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.iojbl.cn/Article/details/gtlegfstya.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtduhneddg.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtgozyqapk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtczhlgtqw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gthmaijham.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvfdawkdw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefaaqsvf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gogol.net.cn/Article/details/gtcayljksj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtdjfsjhya.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtfzmzfnls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtrwzzysyv.html

[D25] Set 集合去重与交并差
来源：http://dali.zycfv.cn/Article/details/gtzzeifqjp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cqqwz.cn/Article/details/gttnitwkeo.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtsbniuxrj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.0kj1m.cn/Article/details/gtdvitpgle.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jlsjyb.cn/Article/details/gtjlvneyyt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtqaxsfutc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwsjxdmv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinqigfzy.top/Article/details/gtgwlptzpj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.meibo888.top/Article/details/gtlmnlhcdk.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtujimblcr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tian-w.cn/Article/details/gttautlibu.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtegyagvoo.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gtiozqvzvw.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtoqdzctmz.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnwogwwy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtcirdntzq.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gthvzjpnkc.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtmktnpndi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpkotrbox.html

E. 字符串处理
来源：http://dali.haohaochexian.top/Article/details/gtqdzwphnl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtiycoflvp.html

[E01] 拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtarmlqejw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hfpthk.cn/Article/details/gtrrbqzwhp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gttzksuspp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtjtwmekbc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtrjwogoon.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtulsimbuv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtaeoowwqt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenzaomai.com/Article/details/gtunzamfqx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtngibntow.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtjbmhuvfo.html

Py:   "ab" * 3
来源：http://dali.sysykeji.top/Article/details/gtlrhyjxbz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.c1oappe.top/Article/details/gtolpxdsxo.html

JS:   "ab".repeat(3)
来源：http://dali.pycfn.com/Article/details/gtwkjxfvwe.html

TS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtbqckipke.html

Java: "ab".repeat(3)
来源：http://dali.guannengcc.top/Article/details/gtpgnxavpf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yongpay.top/Article/details/gtbqixyiec.html

Ruby: "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtojdqobzu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gthbneajnh.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtwkkckorx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtcjgjviaq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtvvwollfi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbcwxqfa.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtnjgglgby.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtrdgvfnib.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtcrjszvdb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtnkvfypkm.html

C#:   s.Substring(1, 3)
来源：http://dali.jyoumei.cn/Article/details/gtgcxrqorb.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtrbghdqub.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtklipdqlu.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gtlamelntg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoombsxk.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtciyblxrz.html

Java: s.indexOf("x")
来源：http://dali.jianghu66.top/Article/details/gtthntcpja.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258888.top/Article/details/gtmpqbcsid.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtrxkijkct.html

C#:   s.IndexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtklwnxssa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtxhpxktca.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbyhboqy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtmsyytmut.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.redwolf501.top/Article/details/gtriyzyyim.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtyxhboqra.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtkttnmsqy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtqasgrdjd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gtsfjnqgef.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtmnrsfmzk.html

[E06] 替换子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadbnrkfk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhongyouzk.top/Article/details/gtodoiaheh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.chenlongwang.top/Article/details/gtqtgsdhqp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtvaolllhg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtmrjihqll.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtfbefaqrd.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtuimexqlk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtvuthsisc.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtokcjknkc.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtdcatwxpy.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gtwulznqrw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gtqfaoupbj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dashuyun.cn/Article/details/gtrywyhbzv.html

TS:   s.split(",")
来源：http://dali.shuidangran.top/Article/details/gtfnactnxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigufen.top/Article/details/gttbkorehz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tianlin.xyz/Article/details/gthyvtiein.html

Ruby: s.split(",");  s.split
来源：http://dali.tianlin.xyz/Article/details/gtsqiucprq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.birdmap.top/Article/details/gtjwlfzkah.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtrxfjvrnc.html

Py:   ",".join(items)
来源：http://dali.nwbrower.top/Article/details/gtoagewxlx.html

PHP:  implode(",", $items);
来源：http://dali.yj202588.top/Article/details/gtdrxgmqjd.html

JS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtwifkhatd.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtqmyqxnov.html

Java: String.join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsnjzoio.html

Go:   strings.Join(items, ",")
来源：http://dali.yj202588.top/Article/details/gthmqjdlal.html

Ruby: items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtfabtfsme.html

C#:   string.Join(",", items)
来源：http://dali.zdqjudy.top/Article/details/gtjnyzqbxk.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gtasdnwstz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gtjeyfpwig.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtahwlkhfh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoamphckc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtzmtnsdjs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtyqseegjn.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangshuangyany.cn/Article/details/gtkxpqlook.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gzhubu.top/Article/details/gtdfhqelhb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtwsbgucgl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtzswfdkoe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtmtcgjega.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gtdfoylffh.html

JS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtgymmmmfw.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtouhzkilb.html

Java: String.format("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtzxufatmb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtcsnwexcd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gthgnwdtxa.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.iojbl.cn/Article/details/gtzdoubzku.html

[E11] 反转字符串
来源：http://dali.yuxming.cn/Article/details/gtwjevhsfm.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtyhnxylzv.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtksszliwy.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqrcighx.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtqojdeeta.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gtaososooy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcqrkhvo.html

Ruby: s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtsdozqxlc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtavxtyiqy.html

[E12] 统计某字符出现次数
来源：http://dali.aizwys.cn/Article/details/gtqaafbchv.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtdydnzgce.html

PHP:  substr_count($s, "a");
来源：http://dali.hnxiangtu.top/Article/details/gtkzktpauh.html

JS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gtrwlwvheh.html

TS:   s.split("a").length - 1
来源：http://dali.zhijiandao.cn/Article/details/gtuflsebfl.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtttgaxflv.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtuicypt.html

Ruby: s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtvdpuuugj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.guowangkeji.top/Article/details/gtpomthapz.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtpcsqgxoq.html

Py:   for ch in s: print(ch)
来源：http://dali.c1oappe.top/Article/details/gtawlhobox.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtefjtjpcz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtmonqvpmm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtyttwvypj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtlhgooczr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.pycfn.com/Article/details/gtjofyvhzo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtltrdtgvs.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtblrwxuef.html

[E14] URL 编码与 Base64
来源：http://dali.cheryme.top/Article/details/gtspisavkn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhoulong.xyz/Article/details/gthksnyqbq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzibjahul.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gtfypljdvj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqytybvqc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daria6918.cn/Article/details/gtuhttaikn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gtnwrgsltp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yangfankeji.com/Article/details/gtogiwaqfg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtumqrukhc.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtmpgsxwjh.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nwbrower.top/Article/details/gtrwxjeady.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.fzhhl.top/Article/details/gtkubyojjp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyjulzni.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gtdjnfabcf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhongyouzk.top/Article/details/gteitrvkix.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sweek.top/Article/details/gtffsihedv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtasvzrgxr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jianghu66.top/Article/details/gtozcgsdqr.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gttozjhdgg.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtftcrqowk.html

PHP:  number_format(1234567);
来源：http://dali.9152youxi.cn/Article/details/gtsmiuabgm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gtknrjvtad.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gtzptuukoa.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtbtpftdll.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtmiwedbjg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtwswnmlsp.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gtbxtotiir.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtvcmqsnjm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtllycdnrz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gtgpvopkww.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkirlmkrp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjxcmjoh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jlsjyb.cn/Article/details/gtkzunbhht.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtzxnsqoip.html

Ruby: s.capitalize
来源：http://dali.yanxiufei.cn/Article/details/gtfvwbmfwb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenzaomai.com/Article/details/gtotordpws.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtzglnwjui.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xziqi.cn/Article/details/gtzxqnehiw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gtakczqaqd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtyoppncia.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gttphiyqvf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtlgleaibj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtnbttfpdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtfrjxmzlb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cqqwz.cn/Article/details/gtojphwjqx.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gtrsronhcl.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtpjmaiymd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtauemkemk.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtnofktjvy.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtanjzhgap.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtagenmvxf.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtrwbvkjsg.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gthsbhnnsh.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtvkugzlsc.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtalnuccyv.html

Py:   if not s:
来源：http://dali.zhongyouzk.top/Article/details/gttamnsvav.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gtrkehgxht.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtfyfhhvto.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthhefkgbg.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gttxhrazqq.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxwmftzk.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtdrrinvsz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbksdtai.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gturwjzsxb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtqxrcjxqp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtpxnxrczi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtykrgwnzi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtmdgvywcm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtyfdlwjtw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtibmldbvk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtkqcsmpbg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtwbjvgvwj.html

[E22] 字节长度与字符长度
来源：http://dali.cdnleiting.top/Article/details/gtyidiljfm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtlrdarbek.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtxxlcayki.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtgnllxvzz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtrwylusxq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtoenigudx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtkygjbhfp.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtdmsoilhl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtoyuxwfcu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvjxqgnk.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtcwreqjok.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlqpsafnu.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtwflepeox.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtnbeqjdoe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtklksdewf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtcewtgpzn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtfjzllxzb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gttcuuimbq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtlyhyhkan.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gteappjmtm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtgpmmcosw.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtkqmjvdtt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gtbunaiubz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtwbyuagyd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtqkqrxdlu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjliuyznc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gthseqsufk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxjiuxct.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtfxlhvcjv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdugwppft.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtoisuxqjm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gthxigqolb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtgbwifnru.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtplgavgzc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtcccflbpx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gtcxbwssgd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtvzafkhqd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtqpnstbmk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtwjhbglsw.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtcggrhbwv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtjvnxbykd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtcncrsuwq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gturroouve.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gthoaedkak.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtyevxvoiz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gtgpwtigtz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtmtordjdh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtjpptzygv.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtxmoebrzz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gtfwmnkynn.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtknxrjosb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtapuxtvrl.html


<!-- 参考信息 -->