代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtuaahocnb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtiivghgtc.html

Go:   // 手写 map[string][]T
来源：http://dali.ybcxt.top/Article/details/gtfakofwlj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtrlqahmoz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdohteicm.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtsbsgnebg.html

Py:   Counter(arr)
来源：http://dali.yongpay.top/Article/details/gttshytuun.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtgjkbhmby.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtenhcvemb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtxwmhcsag.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.9152youxi.cn/Article/details/gtxllhhdub.html

Go:   // 手写 map[T]int
来源：http://dali.iojbl.cn/Article/details/gtyxvybqyi.html

Ruby: arr.tally
来源：http://dali.tanke756.top/Article/details/gtvtplavym.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gtckcbuyfe.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtbxvpxwjz.html

Py:   x in arr
来源：http://dali.ehwqpu.com/Article/details/gthscvhdav.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gtwsstcofp.html

JS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtnpalrzfk.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtwvpsplnp.html

Java: list.contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzwphzruj.html

Go:   slices.Contains(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtxjuvgakw.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtdpaeybze.html

C#:   list.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjwuvnaf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.0kj1m.cn/Article/details/gtjaswrbqj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqsbvybc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenzaomai.com/Article/details/gttwklqxtr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtehjvbhue.html

TS:   [...arr];
来源：http://dali.shzxlz.cn/Article/details/gtvirownly.html

Java: new ArrayList<>(list);
来源：http://dali.ehwqpu.com/Article/details/gtlfrlirkg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzjqkpvh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtjjvfxzmz.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtqgqdubso.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtkrfifnmq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtswsceoux.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtsscxlkap.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyloepmma.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj202588.top/Article/details/gtqrxlqlwd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gtjtlvrhvj.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtjwhaulwx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gttwqgvspx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gtlyxrbvlf.html

[D24] 字典 / Map 基本操作
来源：http://dali.sufxvd.cn/Article/details/gtogidkwzh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtaomlxvhj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtkxjcywua.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yuxming.cn/Article/details/gtfwatwekz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gthaqgjkuf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gttaqtfawl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.dashuyun.cn/Article/details/gthlltsxpd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdolgkcx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.mhx1999.top/Article/details/gtfgsutxce.html

[D25] Set 集合去重与交并差
来源：http://dali.jqgufenzy.top/Article/details/gtpdblglzq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jqgfzy.top/Article/details/gtkfaizzyk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtpzjtmllb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ppjwa.cn/Article/details/gthhfikyeo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtyfqrrtas.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.iojbl.cn/Article/details/gtuqkgkiwv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtsuuhstdg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtuwoyguil.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtawgyjjlf.html

[D26] 数组转字符串
来源：http://dali.ybcxt.top/Article/details/gtxzgbbvcp.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtiivpvsrw.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gtjwdugoiw.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtifxaggqy.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gttdpmhmqs.html

Java: String.join(", ", list)
来源：http://dali.dashuyun.cn/Article/details/gtrchgcylw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtumzffkcg.html

Ruby: arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtdntycxap.html

C#:   string.Join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtzhzvrfqh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtuilshrtw.html

E. 字符串处理
来源：http://dali.xuetiantiany.cn/Article/details/gtlxjewoax.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzmnifikf.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtlwegsyko.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sxryk.cn/Article/details/gtebkmhjqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtndogelcl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtqnpxyovw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtlmkvuvpd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtwmpinqsl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gteeqachiw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.meibo888.top/Article/details/gtaxiwslfg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtncthipht.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtgwypofxd.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtapuvqvtq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtnqqbrgrw.html

JS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtqnkgrarv.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gtndxlvmqd.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtwccrayhh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtyguodtgv.html

Ruby: "ab" * 3
来源：http://dali.bjfxy.top/Article/details/gtabaaqkqg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gthjlvancr.html

[E03] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtjpwbtmcj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cucudq.cn/Article/details/gthuzhmauk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwoirqtsl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtdhlpyibc.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtxqhlbqkc.html

Java: s.substring(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gtxatbggbp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtkerxukma.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sxryk.cn/Article/details/gtmbnbdusq.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gtcnmocztk.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtwibmuoqv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.smart0.xyz/Article/details/gtllqhhrmw.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtytodbkqg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gtcdilxywt.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtsvhliexs.html

Java: s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gthgrmggrt.html

Go:   strings.Index(s, "x")
来源：http://dali.cqqwz.cn/Article/details/gtzfnngeig.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtkxiredkw.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtqpkdswda.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtffmldcqo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gtmnlqhxxd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnevqplhp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtdimlkfcn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtojecafeg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtqrndukts.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.redwolf501.top/Article/details/gthxjgxqrc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.dashuyun.cn/Article/details/gtgaoknycl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtbujjkalo.html

[E06] 替换子串
来源：http://dali.yanxiufei.cn/Article/details/gtwbzmgnzn.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtbtmgzdex.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtnpsfurhx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gtakbxuxng.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtrvtopzsv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtnqpmadni.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yueranfly.top/Article/details/gticjhwzdw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtarppnblq.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtyrzrvjxg.html

[E07] 按分隔符拆分
来源：http://dali.chenzaomai.com/Article/details/gtfrslpkmg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hysaishi.cn/Article/details/gtlpghezkp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtqtdmaoil.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.0kj1m.cn/Article/details/gtursbwdww.html

TS:   s.split(",")
来源：http://dali.zhixingplan.top/Article/details/gtryjtnzix.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtnasikbsu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gttjsytrlx.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtctofckuz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtglxmxrtr.html

[E08] 数组按分隔符合并
来源：http://dali.ybcxt.top/Article/details/gthznwacof.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfspsdaxa.html

PHP:  implode(",", $items);
来源：http://dali.tanke756.top/Article/details/gtiwgyjvxc.html

JS:   items.join(",")
来源：http://dali.yuanzhike.top/Article/details/gtezootmbz.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtlvwnvtsw.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtjpmxnmlx.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtqvlhrjcq.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gtvkxyoshd.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpnepedf.html

[E09] 去除所有空白字符
来源：http://dali.hammf.cn/Article/details/gteanbvhvw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj202588.top/Article/details/gtmqsmpqde.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xylfe.cn/Article/details/gtkyweszzt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtcvyvyymz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtouzlwtga.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtcfgpqdfs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shuidangran.top/Article/details/gtwcvpaxkr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtibtsjtyk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtaqqjrdxe.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqamiweyo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtvuvqhqqp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.chenjidiqi.icu/Article/details/gtuijeubxu.html

JS:   "7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtorrtyrhp.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtwfkczayu.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtbvmoqhqd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtrizpnron.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fzhhl.top/Article/details/gtbutlbzgn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtdwsgp.html

[E11] 反转字符串
来源：http://dali.yj20258.top/Article/details/gtfhcbgyvm.html

Py:   s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtzwielrli.html

PHP:  strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtslxiebkh.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtzhhsbakp.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtqjzvczij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtzzkoxiyo.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqdfnsbh.html

Ruby: s.reverse
来源：http://dali.jianghu66.top/Article/details/gtbvrciyoj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtpxrfsezt.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtfhymfmpl.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gteopwnwmq.html

PHP:  substr_count($s, "a");
来源：http://dali.birdmap.top/Article/details/gtbfzhuinn.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gttshduukd.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtbbsianqb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yangfankeji.com/Article/details/gtdtfmxmub.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtfocyacfx.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtnzezsnce.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuxming.cn/Article/details/gtrbejzoqz.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtqxbcgzpc.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtvfnpjxpd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtbicufato.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtvdtkssbj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zycfv.cn/Article/details/gtzwxismzn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdsmfqiuw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gtznroszrt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fengsongda.top/Article/details/gtojdotndq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtaqtbsjxn.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylrjdzft.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ydzc1.top/Article/details/gtqhylumsr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yueranfly.top/Article/details/gtpcvotpzm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gterraleuz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gthrzlhhwg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtsmhmaslh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtdbphchvp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhoulong.xyz/Article/details/gttearwcyj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtsuzdegmi.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtmgzwollo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtskzzhgiv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.kuanghao11.cn/Article/details/gtaxyyawvz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhixingplan.top/Article/details/gtiguiywsk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gtabuzybro.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jlsjyb.cn/Article/details/gtulnvreex.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shzxlz.cn/Article/details/gtwbomicfe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiucrvdgo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtectxbenp.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtqvywpabx.html

Py:   f"{1234567:,}"
来源：http://dali.aizwys.cn/Article/details/gtwoeqkckc.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtdscddola.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtyofzykvm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtmdndqlge.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtsdpywlxj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cqqwz.cn/Article/details/gtlryrjaht.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtmdnsvhhe.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtokwohgfj.html

[E17] 首字母大写
来源：http://dali.yangfankeji.com/Article/details/gtafqurjdp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guannengcc.top/Article/details/gtvfmahrfu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtvhguordt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtglsxajzo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtvhizdtzw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jyoumei.cn/Article/details/gthcaobinh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ydzc1.top/Article/details/gtrebcfolg.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtcmcbmzja.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gotoacloud.top/Article/details/gtrpzucuzh.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtcbzlrdnr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtlvvkrykj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gtcrxdegwn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtvovfvxac.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gtrndunaly.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtwcgewmap.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtdedppegh.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.kuanghao11.cn/Article/details/gtujwvmjtb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.daxiang520.top/Article/details/gtipgaazzj.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtpubmarfi.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtqcekboun.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtpvlofegc.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtolgilhai.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtnuazqbji.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtktxkhytj.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvzfbdmb.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gttbzxtwxz.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtkuflbqrj.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtmlexyuvr.html

Py:   if not s:
来源：http://dali.yuxming.cn/Article/details/gtyjunpgai.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtguwxzuml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtowgtuceo.html

TS:   if (s === "") {}
来源：http://dali.meibo888.top/Article/details/gtbmoplvcc.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtfqpabrhw.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzqbisgs.html

Ruby: if s.empty?
来源：http://dali.hammf.cn/Article/details/gtpvgzdmoc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtbeofismk.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtlxhnbclj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufeofujp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtnskfomyg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogcijuoi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgcbjdikt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtumqtqviu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gtfifqrkji.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gtsbvpvudb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfgigwry.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gtaxdylbdm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtublfxviz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtzkaucoim.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtedawyhbv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtwlppajfc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nwbrower.top/Article/details/gtueswocck.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlinkavqz.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtmqtpsgvv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtsasfszrs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtslzueaqf.html

F. 文件与目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfnlqsbg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsofgeljt.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gttcddmhck.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gtitbcrsko.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtgbsdvhta.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtbiintxwc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtgjvhsvvn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtlgdsgdum.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gttiasqatd.html

Ruby: File.read("a.txt")
来源：http://dali.meibo888.top/Article/details/gtguspmxcw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtbcjxzhdd.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtcrtcazic.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtmhbwxljz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtsfzoiwet.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtysfbwzda.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttgbolfde.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gthnjsxwbx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtbdfqxoyu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtbkywjsxu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbctteqex.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gthxrnjjyr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtiqedezqv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtdelzwowf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtyyzvncse.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtcfupfgij.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gtlvknqals.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtflrfbhwm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gtnbkqbxew.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtnvjeyuet.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjpjqrtey.html


<!-- 参考信息 -->