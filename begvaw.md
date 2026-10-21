代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtqtxlxyoq.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtafqnugvp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtromctwpo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yonumen.top/Article/details/gtksagebsm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gthoriitnf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmjkehbye.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.quarkkingdee.top/Article/details/gtooxptcbh.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtsrxfcqtt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtcpwmdcrf.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtliiqpxph.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gtflcmpmhz.html

Py:   max(arr);  min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtinyflqfp.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtiqpadjkt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yongpay.top/Article/details/gtvbdgbnci.html

TS:   Math.max(...arr);
来源：http://dali.redwolf501.top/Article/details/gthkwoiwln.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.havefunace.top/Article/details/gtiwtxynkc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yvedp.cn/Article/details/gtdtqismep.html

Ruby: arr.max;  arr.min
来源：http://dali.cashguo.top/Article/details/gtjykodkrx.html

C#:   list.Max();  list.Min()
来源：http://dali.ivvv.top/Article/details/gtgtclpfpw.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtqnbyigbx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yueranfly.top/Article/details/gtoivgjouv.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gtcyrdhjqg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspocirxi.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtpbcccabz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtcakvruat.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gtfzbvvtyt.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtbrocxdfg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtiqojoujn.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtowocyein.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gttnknfbbx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsesbzmnr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnqzz.top/Article/details/gtldtzqeus.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hysaishi.cn/Article/details/gtoetpknxe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtvectuvne.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtvjxwgsid.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtecutjvxd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shangyingyoupin.top/Article/details/gtsqqnqiux.html

[D20] 统计每个元素出现次数
来源：http://dali.yongpay.top/Article/details/gtxygzgxrg.html

Py:   Counter(arr)
来源：http://dali.cdnleiting.top/Article/details/gtpxmjyvre.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gtmusjyxve.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gtslxgezko.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gthggrtwnr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gtsqtfxzhj.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtlwbbqkwr.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtdbposcsx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenzaomai.com/Article/details/gtzpzlszuj.html

[D21] 判断是否包含某元素
来源：http://dali.shzxlz.cn/Article/details/gttuwfgiwn.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtmdzkgsjl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gteekloxwu.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtspsndizn.html

TS:   arr.includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtscadmmnk.html

Java: list.contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtncrrtmmz.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtauskqcns.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gtctscyano.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtodarwhib.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cucudq.cn/Article/details/gtrvyrecjj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.bjfxy.top/Article/details/gtrtwajkxl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gzhubu.top/Article/details/gtggvajpep.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzelkrmig.html

TS:   [...arr];
来源：http://dali.yj20258.top/Article/details/gtnhrbhgiv.html

Java: new ArrayList<>(list);
来源：http://dali.meibo888.top/Article/details/gtcdmumscg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.316326.xyz/Article/details/gtxuizfbqt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gogol.net.cn/Article/details/gthzyfdrho.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtesldjikc.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtpthwiqbk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtrhdbdjem.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.c1oappe.top/Article/details/gtljybzbun.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktrgvmyb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xinyue.icu/Article/details/gtffjnrolf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.haohaochexian.top/Article/details/gtwpzeqajo.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtrazalszg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gtmlpnhssh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sxryk.cn/Article/details/gtdrswhalj.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gtrxpphyac.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gtwxipzqve.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtnqkxhkdv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gtxqwlqgyt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yongpay.top/Article/details/gtkwduchut.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenlongwang.top/Article/details/gtjcznztwn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aibaodan.cn/Article/details/gtuzjuqgqn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnqzz.top/Article/details/gtoddvxoqv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhongyouzk.top/Article/details/gtmpqhipiy.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtsqfwqbkj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gthcnadqhn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shzxlz.cn/Article/details/gtdflnozcd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jiagoushi.top/Article/details/gtveiybzak.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.dashuyun.cn/Article/details/gtizwcqxnw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jianghu66.top/Article/details/gtxffdohqs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtdryadqtm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gtnfdwsggg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtxpycowjr.html

[D26] 数组转字符串
来源：http://dali.xziqi.cn/Article/details/gtwprylpcc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtvpdexiwn.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtojtecqal.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtforfcsbj.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtualicwru.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtrgxtwzob.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gttjstkysd.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcdfdhzz.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtdgfhxfgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtiaqrfpcy.html

E. 字符串处理
来源：http://dali.dianchejie.cn/Article/details/gtnsslflid.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtngcuhkaw.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtxwlzdxgv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtxxplipgj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.birdmap.top/Article/details/gtxwdlygqk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtbnpdmmlt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtehezxcxi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenzaomai.com/Article/details/gtkmzvvsax.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtjmgnkhlo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gtyiupogmw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gtdgquxorz.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtcklgbcjb.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtbsgjhmik.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnuywrfv.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtbpehpxqc.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gtljplzwka.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtrdryqgip.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhoulong.xyz/Article/details/gtpdaibpfy.html

Ruby: "ab" * 3
来源：http://dali.sweek.top/Article/details/gtahwavoog.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pycfn.com/Article/details/gtnuegpvgl.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gteridrvxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtxmxtxslp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtaftrtixy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtxbctuqcq.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtwxsrzvec.html

Java: s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtvtlpahpc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtpavfocdn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hfpthk.cn/Article/details/gtxwvmmdse.html

C#:   s.Substring(1, 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkegofvvt.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtshjvkgje.html

Py:   s.find("x");  s.index("x")
来源：http://dali.meibo888.top/Article/details/gtvmobljdq.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtzqxoznbv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gtpqxydjdu.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtxfsbppdv.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gtdvrmgnzw.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuptyteh.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtneamihld.html

C#:   s.IndexOf("x")
来源：http://dali.guowangkeji.top/Article/details/gtwqyelazj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtqzqjessh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtmkagwalq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.snrcjt.cn/Article/details/gthsoghsfn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtrnxpdf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtiuqxpskm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtnntispie.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtazerqgol.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jianghu66.top/Article/details/gtprjqmnyg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtwfpqlqub.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtpxzfsgwx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmqdnaamf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.ydzc1.top/Article/details/gtochravvo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtdynmvauk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtbpljtjne.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtukquflaq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtigpmrtmj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtobgzxnje.html

C#:   s.Replace("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtexgszhza.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtyzjqqtly.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.quarkkingdee.top/Article/details/gtimyarpds.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtcdloiykb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtlrusdkss.html

TS:   s.split(",")
来源：http://dali.cashguo.top/Article/details/gtxibpedvr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtemhdmefl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtdszjheft.html

Ruby: s.split(",");  s.split
来源：http://dali.wangshuangyany.cn/Article/details/gtlwifxiuu.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtpogejunn.html

[E08] 数组按分隔符合并
来源：http://dali.xuetiantiany.cn/Article/details/gthmxndhyf.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtjteoklst.html

PHP:  implode(",", $items);
来源：http://dali.yueranfly.top/Article/details/gtehtztife.html

JS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtsgpxdvui.html

TS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtlikxfart.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gttxoveylz.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gtxktdhtnl.html

Ruby: items.join(",")
来源：http://dali.hysaishi.cn/Article/details/gtyvsgwiea.html

C#:   string.Join(",", items)
来源：http://dali.yuanzhike.top/Article/details/gtbtyfqpgd.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtiyjyzhan.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gttjlyatdb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtrquabqfu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtvkswuxcg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtlyvkvuac.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258.top/Article/details/gtjvgtmzjz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tanke756.top/Article/details/gtaqvqpeqg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtlmtvjesg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gtivbumlch.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtjkjzrugu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtlsubmogz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xylfe.cn/Article/details/gtlphufmda.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtpqxicsfl.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtvwrojafp.html

Java: String.format("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gtmygpxurs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.wangdashe.top/Article/details/gtpbwzwjwn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtxjbzgtep.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.wangshuangyany.cn/Article/details/gtllsufxyq.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtwgauutup.html

Py:   s[::-1]
来源：http://dali.hnqzz.top/Article/details/gtihrubhbb.html

PHP:  strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtalnifibt.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtxltldybi.html

TS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtvfmpxxnm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtyzbchrqp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgqjykkj.html

Ruby: s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpyxzmsl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtekcjcyjv.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtgqsmeyrz.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gtxzdzvcmo.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtfpnqocqx.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gtspkairkk.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtyldhxjjs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtvffcgahw.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gtpbcfjkiy.html

Ruby: s.count("a")
来源：http://dali.aibaodan.cn/Article/details/gtelnuwfmv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yj20258888.top/Article/details/gtxlwdwhig.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gtvjnzrfep.html

Py:   for ch in s: print(ch)
来源：http://dali.cqqwz.cn/Article/details/gtuktomtbe.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gtulgtezot.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtukkiyyqi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtidzynvji.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gttlbwdgfr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtcldmnzqg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jlsjyb.cn/Article/details/gtptmrqvtm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtnadjagum.html

[E14] URL 编码与 Base64
来源：http://dali.zycfv.cn/Article/details/gtslvkybdg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gtbajckmyd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yongpay.top/Article/details/gtifspiuxa.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gttohvdmif.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtbuembvpp.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtbffraovp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtldrsumzz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gtffzejduz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtxeljiisr.html

[E15] HTML 转义 / 反转义
来源：http://dali.hfpthk.cn/Article/details/gtjsweojnk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.havefunace.top/Article/details/gtxhxfwqrg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tian-w.cn/Article/details/gtjopaavkv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hysaishi.cn/Article/details/gtobiksqxb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtjvitfgpb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sweek.top/Article/details/gtvfnvtiuv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtqiczyydf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtaubjwmxq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtaqcjktbs.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtzyrtujny.html

Py:   f"{1234567:,}"
来源：http://dali.jinqigfzy.top/Article/details/gtkyksdbtp.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtnwoqwubg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtvcofzyry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtjxuyylhf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yvedp.cn/Article/details/gtyacdrmzx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gtlceofmlv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cheryme.top/Article/details/gtodjqsgcp.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gtgeaptslj.html

[E17] 首字母大写
来源：http://dali.nanxuanxn.top/Article/details/gthdxlatdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuanzhike.top/Article/details/gtnztmffof.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtqejnjzvd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtmxqkczyy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hywenlv.cn/Article/details/gtjqakhlyr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gtvpmdferq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtkxmicxbq.html

Ruby: s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtqnyjbksx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtdbofriad.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gtmcrzxnwh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtpgcfznbq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtqwgekxzu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtvhxgfjri.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtljqsyfqf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtvecbtaia.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtxsfygaow.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gtjqpmnjlu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigufen.top/Article/details/gtvidqyvvd.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtqtytfxqc.html

Py:   s.splitlines()
来源：http://dali.xuetiantiany.cn/Article/details/gtipamxkpt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtvjjchwje.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtdgnbqbyc.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtxefjljtp.html

Java: s.lines().toList()
来源：http://dali.mhx1999.top/Article/details/gtxnbxbdgd.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtmkmagopo.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtczqckhsp.html

C#:   s.Split('\n')
来源：http://dali.gaohongyu789.top/Article/details/gtnwzhmbiv.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gtqbvhacho.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtpliifkpw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtrcmilydl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtpfuzmsfa.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gtusbvhnod.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtarqcsylt.html

Go:   if s == "" {}
来源：http://dali.zhoulong.xyz/Article/details/gtazuxhbzc.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtanlvtulj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkszvhwyx.html

[E21] 超长截断加省略号
来源：http://dali.hfpthk.cn/Article/details/gteklinodf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shangyingyoupin.top/Article/details/gtigvlnmrd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtoqczzzfa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtbufyxaks.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyodnwwk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwzphlhd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gtnjxsdqil.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtfenrsbws.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtdalrchht.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtkpexjdur.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtbdrmhtza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtzmlxseee.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtugvmzzff.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtwvwzjbzo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtubnpyziy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gtlexxzktf.html

Ruby: s.bytesize;  s.length
来源：http://dali.svipenyu.cn/Article/details/gtswfbkmoz.html


<!-- 参考信息 -->