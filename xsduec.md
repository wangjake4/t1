代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gtdvrsirzx.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqovhycab.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxmhhckh.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtiyvbcxhh.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtzgjlgaqz.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtelcegaal.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtzciwpkui.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtxgithtgv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtqtqduyqf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtrfjwmxgr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtfpdlunot.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtnnpqnjob.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gtfjhlfekj.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gthrkjczaf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gtiovltzkh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gttulbhdqc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gtdcwhktel.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfpwtlji.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtgljlksyv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.iojbl.cn/Article/details/gthkgystgj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtkpzleasp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtkudqqprm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtzxvztzxt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpkvfgt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtrvejizlh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xylfe.cn/Article/details/gteyvotwdp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioeqlhzd.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtrwcwyrpo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtyupyrvky.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gtwzwltech.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtiuomuxjq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtdcdjrbua.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gthjqorqfo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtswvcnujv.html

PHP:  array_unique($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtdkqugzxt.html

JS:   [...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtxfbwwhku.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtowktowwi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hammf.cn/Article/details/gtkqtdbofd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtarjolzfg.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtcyaqfmam.html

C#:   list.Distinct().ToList()
来源：http://dali.yj202588.top/Article/details/gtuqyrszjp.html

[D16] 求和与平均值
来源：http://dali.xuetiantiany.cn/Article/details/gttczthbqu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gtffrzxfau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gtvylcnbpa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtudlhqjsr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtithccxdr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsahppfr.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtcjxwqkko.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtxiuimbon.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtbqeqapmy.html

[D17] 最大值与最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtlpzwwrek.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkyutrcff.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyjgedal.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtvjuixqsw.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtpmyxpypf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.andypj.xyz/Article/details/gtrxcqyatg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.0kj1m.cn/Article/details/gtphaoyekq.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gtcuvyuoje.html

C#:   list.Max();  list.Min()
来源：http://dali.sxryk.cn/Article/details/gttyhzkxdt.html

[D18] 扁平化嵌套数组
来源：http://dali.zdqjudy.top/Article/details/gtymflgdru.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gteprkoulu.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtymtwdana.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gtdboglttc.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gtdwmdxjct.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtblwxdapg.html

Go:   // 手写双层循环
来源：http://dali.ppjwa.cn/Article/details/gtmvolpymd.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtexjxhuzv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtdexxojwe.html

[D19] 按字段分组
来源：http://dali.ydzc1.top/Article/details/gtuzdcbxmh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gtnllhwspm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.birdmap.top/Article/details/gtsezsvhdy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtssoavjro.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtayiqxccr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ehwqpu.com/Article/details/gtjsbzchdp.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gthpmqtadn.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtbwcbueip.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtrlxspfya.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtzdecgysi.html

Py:   Counter(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtatmzpspa.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gtexwxqoxz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.fzhhl.top/Article/details/gtxhriryad.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtfjbwvpaj.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gtcsaushek.html

Go:   // 手写 map[T]int
来源：http://dali.xinyue.icu/Article/details/gtlalsuqvl.html

Ruby: arr.tally
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrnmmuie.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ehwqpu.com/Article/details/gtbvqtpqzj.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtvvidyygt.html

Py:   x in arr
来源：http://dali.ivvv.top/Article/details/gtfvgaeocr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yonumen.top/Article/details/gttkzsdblc.html

JS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtkucrcquf.html

TS:   arr.includes(x)
来源：http://dali.aizwys.cn/Article/details/gtxefckmar.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gthsawirmh.html

Go:   slices.Contains(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtfglztodi.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtuihjigxm.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtjzrnybaa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkrquuji.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gtzrctvslq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.iojbl.cn/Article/details/gthabmtkxh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtihtehngx.html

TS:   [...arr];
来源：http://dali.hfpthk.cn/Article/details/gtngopwdjq.html

Java: new ArrayList<>(list);
来源：http://dali.havefunace.top/Article/details/gtweqsvlzu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtmyaibcda.html

Ruby: arr.dup;  arr.clone
来源：http://dali.daxiang520.top/Article/details/gtklpybjun.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gtrxybehps.html

[D23] reduce 累积计算
来源：http://dali.nanxuanxn.top/Article/details/gthvkcfzpi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jyoumei.cn/Article/details/gtkfxvdhgz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtzwncvrys.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtugjqkpxn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmkfxcll.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.iojbl.cn/Article/details/gtnjcttjfh.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtifppwuof.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlszwlafc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtqfrfbdht.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtzbnbduiz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtvyboftlf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtkluegsbg.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtqzksjolc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.c1oappe.top/Article/details/gttcswxrmh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gtygznxcjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqlacucz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gtjntzzksn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.9152youxi.cn/Article/details/gtfrjlejcu.html

[D25] Set 集合去重与交并差
来源：http://dali.gzhubu.top/Article/details/gtxwthooki.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigfzy.top/Article/details/gtswfcepcu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtkoccojqm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.haohaochexian.top/Article/details/gtmscabnqr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.9152youxi.cn/Article/details/gtjfehtpug.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtwsbjotgy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbnienmz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtixqepuff.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtwoljedhx.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtvvfrzfil.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtkhqtoghl.html

PHP:  implode(", ", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gttekfokbr.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtrlwpqllk.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtcjwbrjmj.html

Java: String.join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtyilpczww.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtfrwgjlkl.html

Ruby: arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gteuytpztu.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtfqlifbht.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmsqtykks.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtysmweizp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbwhpbkum.html

[E01] 拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtxsosodaw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtvlvhnpnt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gtnbogvllr.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuanzhike.top/Article/details/gtdpryxtze.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gttzojcgia.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtyovsmzuj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gtygjilksa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtyggmlisf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtttisakkq.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gttxglhwpz.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtrmycqaep.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gtvfknczvr.html

JS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtzspqqmvf.html

TS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtpwulatze.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtjlpvufkx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtjykalcfa.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtkkuphvxl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtukxecuez.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtdclfihod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.birdmap.top/Article/details/gtdietazfz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtxhyduyua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtpciutydc.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtuamtdwoo.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtcjycyzut.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gtlhlervoj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gtsrosfzsw.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gtkypzjcjn.html

[E04] 查找子串位置
来源：http://dali.quarkkingdee.top/Article/details/gtcfbquzvi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuctjvdxy.html

PHP:  strpos($s, "x");
来源：http://dali.tanke756.top/Article/details/gtnfinvqfg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtghtgxsed.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtrzmaudxa.html

Java: s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtnepyugcp.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtaunbiubg.html

Ruby: s.index("x")
来源：http://dali.yj202588.top/Article/details/gtcxmnxsaz.html

C#:   s.IndexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gthdxndlbu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yonumen.top/Article/details/gtaprvgxon.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtdgetcimr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhiwuduotai.top/Article/details/gtxivjngwg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtncnzbfwi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gtpkejjyua.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmecyaphu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtzbhhuapc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtdtuqskor.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gthcylbvsf.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrncvphc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtrtsqdnon.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtcwaemnqy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtrvqkkidu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtsgjhtyhf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtgfxkfwnh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gttvgmltsa.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvlselzd.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtkqmxyyjj.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gtlcqkrfnr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gtcnpeqeud.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqjtyyjcc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtdaiusvsv.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtatyowqdy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jyoumei.cn/Article/details/gttugfgjdg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sysykeji.top/Article/details/gtbexrhmff.html

Ruby: s.split(",");  s.split
来源：http://dali.hywenlv.cn/Article/details/gterrwgahe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.nwbrower.top/Article/details/gthvyarjno.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gtipaeqjll.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtrbtwlxwe.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtqxrtjotn.html

JS:   items.join(",")
来源：http://dali.tian-w.cn/Article/details/gtvamebayk.html

TS:   items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtvddjldna.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtmeksdnpi.html

Go:   strings.Join(items, ",")
来源：http://dali.iojbl.cn/Article/details/gtpblzmjvv.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gtikrpitoj.html

C#:   string.Join(",", items)
来源：http://dali.xinyue.icu/Article/details/gtfaerebly.html

[E09] 去除所有空白字符
来源：http://dali.hfpthk.cn/Article/details/gtrvjvopyw.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gtytsvuymb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtyxiesocz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtjrzxbvnf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtbvarayqg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtusjkohru.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtebfecwve.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtpulzbauv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yj20258.top/Article/details/gtvjuwmxjp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gtdzdeqftq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggrfscbh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuanzx.com/Article/details/gtziwwsflf.html

JS:   "7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gtghkrlgty.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtfiodvguj.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtsykyshjb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtuwmpdhjq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtbmfcyspn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtwbsxmwff.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gttzlyiyuf.html

Py:   s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtouxkpzso.html

PHP:  strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gtwgcyvwvp.html

JS:   [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtikbmqhlk.html

TS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtazxmntuj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cdnleiting.top/Article/details/gtllofgbqj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtcscrhtgf.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtphvqxzhg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gttbkldrmr.html

[E12] 统计某字符出现次数
来源：http://dali.0kj1m.cn/Article/details/gtnahypubn.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtbneaqimi.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gthhfbsvfn.html

JS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtsfqfsret.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtvftisnlz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhiwuduotai.top/Article/details/gtrnmyhyvq.html

Go:   strings.Count(s, "a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwlwgizd.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtbzfnsutm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtzthnggnb.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gtuvyzrtnz.html

Py:   for ch in s: print(ch)
来源：http://dali.andypj.xyz/Article/details/gtfnrminxx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenjidiqi.icu/Article/details/gtynhhqgsx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gtesrdlbgj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtanftlnry.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtddhfugnv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gtxuygzbby.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtyaogdstc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtunvwtwwf.html

[E14] URL 编码与 Base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrxboasz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cheryme.top/Article/details/gtfxxdhzvv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gtwazdwqha.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gtdzbyvrnm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gtpwyptxsh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtzmnfzowk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.0kj1m.cn/Article/details/gtxpctsigw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jianghu66.top/Article/details/gtmjmzvziz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zdqjudy.top/Article/details/gteqokhaer.html

[E15] HTML 转义 / 反转义
来源：http://dali.hammf.cn/Article/details/gtietysebn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjuwgdfmy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xylfe.cn/Article/details/gtvgpzqpbh.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yuxming.cn/Article/details/gtblqqkffj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtljuacmln.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtpnefqurc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyibyawoy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.fzhhl.top/Article/details/gtdhudsido.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtdvktcqyc.html

[E16] 数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtrfchqtwm.html

Py:   f"{1234567:,}"
来源：http://dali.iojbl.cn/Article/details/gtzizbaxvh.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtfffxkctv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtjrqqnpeh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sysykeji.top/Article/details/gtnwsevmxb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtyfsejhab.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zycfv.cn/Article/details/gtyjcajfza.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gttqptxxdj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhoulong.xyz/Article/details/gtsnpakxny.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gttlmqryyo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daxiang520.top/Article/details/gtcovfyndg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.iojbl.cn/Article/details/gtmwweagxx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtfmbifdww.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtmiapypca.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtadzvqoga.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gteftyurux.html

Ruby: s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtxloicknd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtbyltcznk.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtwppnornh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtledegssy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtgaemovln.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtpfxawqzq.html


<!-- 参考信息 -->