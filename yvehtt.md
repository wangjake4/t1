代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gt2ppjhlnns.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2pfrmaaei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2ibnvxrcn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.havefunace.top/Article/details/gt2cevyfvhy.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2lalpymkf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2fmnelbgy.html

PHP:  array_unique($arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2yyotcfqm.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2fhwdcbzc.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gt2yybdowdo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gt2dzckdrow.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gt2vgmuboqa.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2errsgbgy.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2mfjgcqjl.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gt2uxihqktx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2szxesmzc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2nlqlqlmt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tian-w.cn/Article/details/gt2jnxwbvsj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.iojbl.cn/Article/details/gt2hwxuvhcp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gt2kyivglpt.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gt2uuqfiitl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.meibo888.top/Article/details/gt2pffaoysg.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gt2uxmljije.html

[D17] 最大值与最小值
来源：http://dali.hfpthk.cn/Article/details/gt2wuceckzw.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2beticxek.html

PHP:  max($arr);  min($arr);
来源：http://dali.yueranfly.top/Article/details/gt2jrtikuta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj20258.top/Article/details/gt2tawcoxch.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2jhiaqoia.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yvedp.cn/Article/details/gt2fchwugcx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgdrzvec.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2rcomhzqo.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2qhqjhilf.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbnnbwrb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gt2ubyffuow.html

PHP:  array_merge(...$nested);
来源：http://dali.kuanghao11.cn/Article/details/gt2souaojuj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.quarkkingdee.top/Article/details/gt2ixabcwnl.html

TS:   nested.flat();
来源：http://dali.yanxiufei.cn/Article/details/gt2omkeqdzs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2lrdzitgz.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gt2kuuepeie.html

Ruby: nested.flatten
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbqwbchx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2jjtuqlpd.html

[D19] 按字段分组
来源：http://dali.hnxiangtu.top/Article/details/gt2vaoerapy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2hfcomxgh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.quarkkingdee.top/Article/details/gt2cyjahuai.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gt2hjvjmxjm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2qybswcdw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gt2tcoqolfg.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gt2xbnxrjrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.smart0.xyz/Article/details/gt2pzezqsqf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gt2nuqizadq.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2lagtkvdz.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2gyqbstve.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmjurbju.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2tmaphawk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tblojkac.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gt2smtnaccw.html

Go:   // 手写 map[T]int
来源：http://dali.hnqzz.top/Article/details/gt2whqgroao.html

Ruby: arr.tally
来源：http://dali.tian-w.cn/Article/details/gt2mxnvbuwd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cucudq.cn/Article/details/gt2sizpcdwn.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigufen.top/Article/details/gt2xsuvdqtg.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gseodkbq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2tjzqwbxp.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2pzhkgify.html

TS:   arr.includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ecsfxyqt.html

Java: list.contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2isbxuxdc.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2ixnckarw.html

Ruby: arr.include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2uicnxxyk.html

C#:   list.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ibpviosd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigufen.top/Article/details/gt2wdamltry.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2otakhead.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.havefunace.top/Article/details/gt2ksbmykno.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wuhfltti.html

TS:   [...arr];
来源：http://dali.xylfe.cn/Article/details/gt2azkvwzdr.html

Java: new ArrayList<>(list);
来源：http://dali.0kj1m.cn/Article/details/gt2sngdmqdi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.vqdsnc.cn/Article/details/gt2vnvtydst.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gt2nyfgpwll.html

C#:   new List<int>(list);
来源：http://dali.yj20258888.top/Article/details/gt2fpjflgmf.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gt2tjzzdzjj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gt2aqxupffe.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2nmspsxit.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2vvudllbs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2fansgevb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gt2piekxjxv.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gt2ckmmmwkv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.nanxuanxn.top/Article/details/gt2imbbccve.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gt2wdtttuff.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gt2pvfqphry.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.haohaochexian.top/Article/details/gt2rfhsfhne.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gt2jxqcgrsa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhengqikj.top/Article/details/gt2kjjuaeuj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2tozfbpva.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gt2eujlnmbq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gt2xgmqzazc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yonumen.top/Article/details/gt2xndicpls.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuanzhike.top/Article/details/gt2yjduzokd.html

[D25] Set 集合去重与交并差
来源：http://dali.yvedp.cn/Article/details/gt2cjfnmdbj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cheryme.top/Article/details/gt2hjjpwtfd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gt2cohaqses.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2coiniddc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gt2jgxsrzyr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ljkgeuvh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gt2wwarrjxk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shzxlz.cn/Article/details/gt2mcurychj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gt2eclbdnrz.html

[D26] 数组转字符串
来源：http://dali.nwbrower.top/Article/details/gt2onpqntro.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2mxedrojr.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2ghvvtxqr.html

JS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gt2xvevuqox.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2fknlaazs.html

Java: String.join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyppkzry.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pecrvxke.html

Ruby: arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gt2ahjtghez.html

C#:   string.Join(", ", list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibxdeuqd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwgstjng.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gt2gojagezb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljuhekwn.html

[E01] 拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2qengxbbt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gt2yslupoiy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2gjanvfhh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gt2rblgndwu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gt2tkjofbds.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gaohongyu789.top/Article/details/gt2bjemvxbi.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2wmktugxk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2vkwgmvzw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2bdxhbysp.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2emzjfbtm.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2sanejbpo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2owpdiugd.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2prwdquio.html

TS:   "ab".repeat(3)
来源：http://dali.cucudq.cn/Article/details/gt2ieeagvch.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2zuxgobui.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.9152youxi.cn/Article/details/gt2kzzrodxp.html

Ruby: "ab" * 3
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltfbvzon.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2ryqovepj.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gt2ykmnpmzg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hirxinsj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2kkvhcpts.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fzhhl.top/Article/details/gt2aigsmrzr.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adtanjvu.html

Java: s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2wmyfoild.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2wkedjhvt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gt2hpiomspw.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gt2nkpfguhn.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gt2nvyqzztl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2xreccmyn.html

PHP:  strpos($s, "x");
来源：http://dali.yuxming.cn/Article/details/gt2jipkpwic.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2bzcaxght.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqjyijjs.html

Java: s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vodscarf.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gt2wrxtperz.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2xggnwxua.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gt2hwgacfxj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gt2sulopngt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gt2fvfkywim.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.aizwys.cn/Article/details/gt2ihnatmsp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.316326.xyz/Article/details/gt2cgmbjztp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gt2mrurqjwh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gt2qzshoyyz.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gt2ivxdvtel.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2umvugohp.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2dweqkmuq.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gt2ynzwiuso.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gt2khzmemfe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gt2mspwessx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbutvkho.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2veollxir.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2vtedxiot.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2xrstbjnm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdmxzcta.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2jcydxixz.html

[E07] 按分隔符拆分
来源：http://dali.quarkkingdee.top/Article/details/gt2sjuyrohm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwcevjzs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2dqtywzfa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangdashe.top/Article/details/gt2sxsqcmkr.html

TS:   s.split(",")
来源：http://dali.hnqzz.top/Article/details/gt2mvqagmfo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrnyxlgh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dcsnplgn.html

Ruby: s.split(",");  s.split
来源：http://dali.sxryk.cn/Article/details/gt2fuepopih.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2updunltx.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2jldximqr.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2pgjfwblg.html

PHP:  implode(",", $items);
来源：http://dali.hammf.cn/Article/details/gt2ngqfccxf.html

JS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gt2yciyztwe.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yxoxqmya.html

Java: String.join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eeifeort.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gt2ozcpsbos.html

Ruby: items.join(",")
来源：http://dali.mhx1999.top/Article/details/gt2hunhczpj.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkoidypj.html

[E09] 去除所有空白字符
来源：http://dali.wangdashe.top/Article/details/gt2wokoesfq.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gt2mprwdyik.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2qssdidqn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2tutvzcpr.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigufen.top/Article/details/gt2nklolges.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2vexthhei.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.sufxvd.cn/Article/details/gt2adqmiecb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gt2eeiswiyz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gt2ibjmatzn.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhixingplan.top/Article/details/gt2xjqgdyvu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knltszgr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gt2lkkgeijt.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gt2sxxoulec.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2xrjomhsx.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzibkbsz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzgwhoph.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gt2levajfst.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.redwolf501.top/Article/details/gt2qtipajze.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2sxzcrcfc.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2zrgzrarh.html

PHP:  strrev($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmouxreo.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2iqzvbota.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2rwdnuczb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gt2xcqpxeol.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ydzc1.top/Article/details/gt2pexpubvz.html

Ruby: s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgwkoiwu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2myevihya.html

[E12] 统计某字符出现次数
来源：http://dali.shuidangran.top/Article/details/gt2qoguoqxn.html

Py:   s.count("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhixvxqy.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gt2fmrumlzh.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2yozzihqj.html

TS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyqfxlxi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2npxsnvgi.html

Go:   strings.Count(s, "a")
来源：http://dali.zhoulong.xyz/Article/details/gt2vqtrfzwk.html

Ruby: s.count("a")
来源：http://dali.nwbrower.top/Article/details/gt2fjukjowz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aibaodan.cn/Article/details/gt2orvrdhli.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gt2dlgglwag.html

Py:   for ch in s: print(ch)
来源：http://dali.meibo888.top/Article/details/gt2aubhykcm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2yelkvquw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2cfnldyjn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2dqbzeozm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gt2pjgmjtbs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gt2cwzvexnn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258.top/Article/details/gt2bipiwngp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gt2yrkuyrzk.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2jzxrtgoj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.andypj.xyz/Article/details/gt2tgvfjhbm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gt2zsimqzwv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gt2kgnvecfv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ubqrrpsh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2yaigfyst.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gt2atzriadn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gt2bpyqiesj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gt2ampfrrch.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2thomhjuu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2daquagjo.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gt2zbauomcj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gt2ngueasfb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2yjzhqskh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gt2nhmdlsra.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangdashe.top/Article/details/gt2gwjzcnmh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.mhx1999.top/Article/details/gt2qhfpurdh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gt2htnkesen.html

[E16] 数字千分位
来源：http://dali.pengpengdd.cyou/Article/details/gt2gepmsfvf.html

Py:   f"{1234567:,}"
来源：http://dali.yanxiufei.cn/Article/details/gt2stsprzmg.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usbwkdbd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2uoygyhni.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2bwinbxkj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2jnzueuvt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gt2nzyqebqe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zycfv.cn/Article/details/gt2qxxpbhze.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2rznyanqg.html

[E17] 首字母大写
来源：http://dali.hammf.cn/Article/details/gt2gihlkhzo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2lhcjsrzu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2cgyzvrxn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gt2qeheupnc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2xoyywxpp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ejhrtznu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2qjprzwhv.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2dpfavwfg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gt2fulqxanp.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gfncmwxy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gt2gceaznjw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gzhubu.top/Article/details/gt2jrxdreyc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2wnrksveh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcqilyfs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2hvcyibvh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2qhpihwgw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gt2osfhbbps.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2jqulzvty.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2ljubkoyn.html

Py:   s.splitlines()
来源：http://dali.nanxinkj.top/Article/details/gt2yxusjmgu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dianchejie.cn/Article/details/gt2oldpkpsx.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gt2ojghezfu.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2ywayetsj.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhrinlph.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2kllmifqg.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2qtbminta.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gt2gaqsuilr.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2pociepoj.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gt2yodcwqrl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccovwwlo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gt2ggivrmhk.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gt2rukmxvph.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2qofbymit.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gt2noeckrxs.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2yattmutq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2atokerae.html

[E21] 超长截断加省略号
来源：http://dali.havefunace.top/Article/details/gt2gsocdzjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj202588.top/Article/details/gt2gdmzokzt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2msqazgqb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2cvklnsam.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2jglghwku.html


<!-- 参考信息 -->