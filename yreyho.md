代发 wailian999

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2rqgiwhxv.html

Go:   // 手写循环
来源：http://dali.cashguo.top/Article/details/gt2uzfydzal.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tian-w.cn/Article/details/gt2fnxfvkdn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2mpzvqrcg.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gt2ownkzeha.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gt2yfmjhvmu.html

PHP:  array_unique($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2fcewqxun.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2ikstypif.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2zazjlzjo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gt2iswzcxie.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gt2ntrnthgc.html

Ruby: arr.uniq
来源：http://dali.9152youxi.cn/Article/details/gt2bzifhkgu.html

C#:   list.Distinct().ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2nxcxqlrm.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gt2ycsnyifd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gt2vhwtkial.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2knbskkej.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkfjvyqc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2mgftgslt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gt2xeptkbwi.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfpirrba.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gt2yqpypjfv.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gt2oasvdxbb.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gt2gzjbdxky.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gt2hnttlnbf.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2sjhcdrnl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gt2tjzgfgzz.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2givlmild.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gt2uprzxipp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jwnhxnnm.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gt2rupdvedl.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gt2qoecruww.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2csjgsvib.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenjidiqi.icu/Article/details/gt2axyncqbw.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gt2ijhhnbxu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gt2nrhckalr.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gt2oewalogs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2bxhxpzqd.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gt2jdcfsjdw.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gt2mizguczv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2lecmpcds.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gt2upnruqox.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2dcbryuxh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2itwavgsa.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xuanzx.com/Article/details/gt2prwogube.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2mrzgzhka.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.havefunace.top/Article/details/gt2rvntdzsa.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gt2kqmdzbyi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gt2ojtzdkok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsvbmlzl.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gt2ijrjoxrs.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gt2pnoupxpb.html

PHP:  array_count_values($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2qhmpndrf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2deqvyemu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cheryme.top/Article/details/gt2dubmqztu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gt2jvbvohgp.html

Go:   // 手写 map[T]int
来源：http://dali.daria6918.cn/Article/details/gt2qgonrths.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2cbcnwgud.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xuetiantiany.cn/Article/details/gt2iougczvp.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gt2zkpnnfiq.html

Py:   x in arr
来源：http://dali.yvedp.cn/Article/details/gt2mcziadnx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gt2uqukooux.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2cjigolrh.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2odhllgpx.html

Java: list.contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2grhvuocv.html

Go:   slices.Contains(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2vhdopawh.html

Ruby: arr.include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzaqrklf.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2lzuyqkkv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gt2ixfiiznw.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2objroffh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtaosdtd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnxiangtu.top/Article/details/gt2phmspodr.html

TS:   [...arr];
来源：http://dali.daria6918.cn/Article/details/gt2wdwookkd.html

Java: new ArrayList<>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2semuswiw.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gt2xxgjjuou.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xziqi.cn/Article/details/gt2zdstqisa.html

C#:   new List<int>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtzmhyjb.html

[D23] reduce 累积计算
来源：http://dali.hywenlv.cn/Article/details/gt2yzdnolok.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdyreniq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.birdmap.top/Article/details/gt2rdrlmumc.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glpopjvz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2rhlaxsuy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gt2ugryrunt.html

Go:   // 手写循环
来源：http://dali.cqqwz.cn/Article/details/gt2kzihtqaf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkqxxvcp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2wpnefxut.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lecjtvrg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gt2osawrjyg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258.top/Article/details/gt2nptooyke.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258888.top/Article/details/gt2iziuslsf.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcunccsn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2sjggduok.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gt2nkpdkpgr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shzxlz.cn/Article/details/gt2xnwtzndk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvptpzow.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehxpmnrq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnycyynq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2ueuzknsw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xylfe.cn/Article/details/gt2slupaygs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuttysrs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinqigufen.top/Article/details/gt2trqsoxnn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yueranfly.top/Article/details/gt2vnchkbtn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gt2yzwmawvf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gt2fsdbhawc.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gt2pshqwamu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsthbljf.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsqymkrz.html

JS:   arr.join(", ")
来源：http://dali.zhengqikj.top/Article/details/gt2cbfbrqpo.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpdvwgpl.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2vyywkakt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gt2uebcmjrc.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gt2mjhbcoat.html

C#:   string.Join(", ", list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bizizzqu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2nadqsiuq.html

E. 字符串处理
来源：http://dali.meibo888.top/Article/details/gt2pljocpws.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2cyuxnqbb.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2znkorhds.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gt2ymutbchu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gt2wsfaoyvc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gt2jlkwrhhi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gt2cyadiwzc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gzhubu.top/Article/details/gt2kpscdgde.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxinkj.top/Article/details/gt2fbstsioe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgfzy.top/Article/details/gt2nmjcgket.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2ivgvksso.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gt2ocktlzwa.html

Py:   "ab" * 3
来源：http://dali.aizwys.cn/Article/details/gt2ejxzupgd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gt2kjudhrkq.html

JS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2oyvsmbiz.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gt2kuuoknde.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2chkhvwfg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2nwmamgoj.html

Ruby: "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gt2ituqyuoj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2uoyxhcbx.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gt2whcqpqqm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2snehvooi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2lsyvpbcm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2gdjcmgwn.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2rmtayzvi.html

Java: s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gt2hvsmbkfz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2rohvdyln.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gt2hmoonjbq.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2wknpekhe.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gt2jtjkdwde.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gt2jmeckjsi.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gt2tkwfcrtr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bkosvywg.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gt2wbbravjh.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvijuqye.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gt2npkuxjsr.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gt2eztvzmot.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2dbhqvoiw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2smutfizn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2bzllxfkx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gt2lwuelcfb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2wtavqvwb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tavjnjoc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2ojnbenad.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpvfloru.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shzxlz.cn/Article/details/gt2wfffjdke.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gt2xvirjuxz.html

[E06] 替换子串
来源：http://dali.jinqigufen.top/Article/details/gt2vczijswr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2cgdzthcd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sysykeji.top/Article/details/gt2oiijfjna.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gt2xjfqvzzh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2tqymutvc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2xaldkqui.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gt2tmyivvbp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2ytmkwuzv.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2rkgftzzl.html

[E07] 按分隔符拆分
来源：http://dali.daxiang520.top/Article/details/gt2nkbqwmqw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.havefunace.top/Article/details/gt2hnpunxlp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2tnzaylhk.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gt2qtsglcgf.html

TS:   s.split(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2salyafce.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.9152youxi.cn/Article/details/gt2qiccahaw.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2djxtuuzy.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gt2wufjkkae.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gt2zfllspyn.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gt2aoxgvfat.html

Py:   ",".join(items)
来源：http://dali.c1oappe.top/Article/details/gt2brufjuul.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gt2blitwdug.html

JS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gt2jrgnriob.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gt2jsrszfca.html

Java: String.join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2bdvwvzir.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2zhmpmmbl.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2bakbosfm.html

C#:   string.Join(",", items)
来源：http://dali.bjfxy.top/Article/details/gt2waepyswx.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2shzoyaxx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gt2yurqdbjg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuxming.cn/Article/details/gt2egvfyabm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2eipfzcyo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gt2cequqsvr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhongyouzk.top/Article/details/gt2gzmjnjia.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2fjxwrvod.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.gaohongyu789.top/Article/details/gt2cectgobo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2fvtzctmf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gt2mabssjvz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2whgbwkop.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gt2bmsmhifh.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfftkwbe.html

TS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gt2wqbqyqib.html

Java: String.format("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2otnphrwp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2xkricudm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gt2jeknbhtj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cdnleiting.top/Article/details/gt2wgncydct.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gt2ijablzyz.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2rfxevhao.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2ouzktdbk.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2iqxkcfwv.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqzzugnu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2omgmzmtk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gt2osgelyhj.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gt2direnjwv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2mlqtuilw.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2sufwckpp.html

Py:   s.count("a")
来源：http://dali.hammf.cn/Article/details/gt2fhrllqfn.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2bgzjqpab.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2vbldcanm.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2hwccerdy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2iiyukoyd.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gt2tobytfuu.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2xflbedyl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2xjesbkgz.html

[E13] 逐字符遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ykhldesp.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gt2cwsazirb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gt2snlubzch.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkdviokr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.pycfn.com/Article/details/gt2dnxrkich.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqzjvpn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.redwolf501.top/Article/details/gt2hhiedtsq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yuxming.cn/Article/details/gt2lvcdncwn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2szqianpf.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gt2stgtvhmh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.vqdsnc.cn/Article/details/gt2sudixvsv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.316326.xyz/Article/details/gt2ffmfwhji.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zycfv.cn/Article/details/gt2vbcnxlly.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huvffjtz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2bbisdepp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilwgakmu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenlongwang.top/Article/details/gt2yadybeow.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2scdkgwmq.html

[E15] HTML 转义 / 反转义
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfmdipbt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigufen.top/Article/details/gt2uukfblls.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gt2psavnekf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gt2uleqenlu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2ktxspsqo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.guannengcc.top/Article/details/gt2mrhkbrwz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jasgzfnc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gt2btzgsieh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.bjfxy.top/Article/details/gt2xmbxknqp.html

[E16] 数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdsyiczb.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2djubheim.html

PHP:  number_format(1234567);
来源：http://dali.xinyue.icu/Article/details/gt2xqvrufiu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gt2ugwsvgwm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2sliyrbxl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufitmmhg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gt2llxagkju.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gt2tbdxhuoo.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2fswducti.html

[E17] 首字母大写
来源：http://dali.meibo888.top/Article/details/gt2itrgzvti.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gt2llxplvmn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guowangkeji.top/Article/details/gt2uozijdhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gt2yugpvsdq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2jiyxowtb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ybcxt.top/Article/details/gt2vdijlkxn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2vrrfizxy.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gt2kfbuhvel.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpagefza.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gt2xmnzxcgc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gt2iqefiwoh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.316326.xyz/Article/details/gt2xhvcofgb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2lkvgjuun.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2lerqzvbg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2buvfnjrl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2irarfwjn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2gdmxwbnm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gt2zfuswhoo.html

[E19] 多行文本按行拆分
来源：http://dali.yj202588.top/Article/details/gt2cufdafuj.html

Py:   s.splitlines()
来源：http://dali.yuxming.cn/Article/details/gt2zewjycdo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tianlin.xyz/Article/details/gt2tlnduxxn.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kojzddvw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gt2jhfiwhkw.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2raruqosd.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gt2nomiyxat.html

Ruby: s.lines
来源：http://dali.vqdsnc.cn/Article/details/gt2tcnmomhx.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gt2nqpdvlgl.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2pucuxtpm.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2urnyyacy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2rmgyldwg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bevrgsgz.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gt2dmjnrvos.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2qegfxvav.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2bsoloydp.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gt2olcreznp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2tjakcwfm.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gt2bfdqfzns.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2equjaqbm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2tjhzntmt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2qpdhvnuq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2urzbesan.html


<!-- 参考信息 -->