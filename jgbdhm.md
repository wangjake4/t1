代发 wailian999

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gthflatihl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtthyaewqs.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbcpjmgp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtqtjrcung.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gthyufkfok.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtlnowfwbk.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtsxbnwnab.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gtstibubbj.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtufdxqvzj.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gtlbsocnru.html

Py:   arr.index(x);  x in arr
来源：http://dali.fengsongda.top/Article/details/gthkcaxeyd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtqovcpghr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtnnztktuu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gtthwvkqbs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtbndsfwyl.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtyzkbufvu.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtmhehbbld.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gtolsexuiz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.bjfxy.top/Article/details/gtzjbtoyoz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtgrydpubl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuudxbtfi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtczzeyhdj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtakgspkzm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtgcmcksjo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtbmwqqizl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtaqhnzrfc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.bjfxy.top/Article/details/gtckbhxpjp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gtvoyglien.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtduzgnjgu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtwmwlzpat.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtrswlgydv.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtitlyihmw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hfpthk.cn/Article/details/gtlopwoewz.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtqkoupttb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtogcdewjl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtzilyvbbp.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtowineqck.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtqsbdddmt.html

PHP:  array_unique($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtsyycuwvp.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtylwxkthr.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtfqleqxfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhengqikj.top/Article/details/gtwgusuxgj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.tian-w.cn/Article/details/gtljkppqyv.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtpqmeevbl.html

C#:   list.Distinct().ToList()
来源：http://dali.jiagoushi.top/Article/details/gtoimpqydc.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtaurzprjq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gtuxaviwgs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.iojbl.cn/Article/details/gtgkzykpvu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtmtjiphcr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtdjtyoeul.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuetiantiany.cn/Article/details/gtmdpvbrqz.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtfxffbyhj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ppjwa.cn/Article/details/gtlzgrkhda.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gttvghktcb.html

[D17] 最大值与最小值
来源：http://dali.jqgufenzy.top/Article/details/gtxusubrpg.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtkvohhsnd.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigufen.top/Article/details/gtwgseclvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtsaqdijlf.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtaarthlbi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtkkentnbk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhxekvit.html

Ruby: arr.max;  arr.min
来源：http://dali.chenjidiqi.icu/Article/details/gtatrsrrpk.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtsmsxigyl.html

[D18] 扁平化嵌套数组
来源：http://dali.daxiang520.top/Article/details/gtizvechih.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hnqzz.top/Article/details/gtuapucplu.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxqouodj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jianghu66.top/Article/details/gtkykclcux.html

TS:   nested.flat();
来源：http://dali.sxryk.cn/Article/details/gtzrnyqyoo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtiimovjpj.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtetfvlyxr.html

Ruby: nested.flatten
来源：http://dali.birdmap.top/Article/details/gtcsmareba.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtcekmhwjj.html

[D19] 按字段分组
来源：http://dali.guowangkeji.top/Article/details/gtlnsirlgf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcxdwpjx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.316326.xyz/Article/details/gtmdbuokhw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.wangshuangyany.cn/Article/details/gtcxdlyayh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtmhwgpewa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtjaakxcus.html

Go:   // 手写 map[string][]T
来源：http://dali.yuxming.cn/Article/details/gtqmpxhbxg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtxyffcbpp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtdvcmeyxz.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtmeanppkl.html

Py:   Counter(arr)
来源：http://dali.ivvv.top/Article/details/gtrtpszhag.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtoybrdqfe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtwdataooq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtsepusuyv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xylfe.cn/Article/details/gtiqcmudbr.html

Go:   // 手写 map[T]int
来源：http://dali.smart0.xyz/Article/details/gtfbbuyjoo.html

Ruby: arr.tally
来源：http://dali.feifeiyinyue.top/Article/details/gtwcevbvnv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.9152youxi.cn/Article/details/gttoknyorq.html

[D21] 判断是否包含某元素
来源：http://dali.tian-w.cn/Article/details/gtppiuwqut.html

Py:   x in arr
来源：http://dali.316326.xyz/Article/details/gtxjendyot.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gtdncvgani.html

JS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtrbltajsd.html

TS:   arr.includes(x)
来源：http://dali.cheryme.top/Article/details/gttgwygcqz.html

Java: list.contains(x)
来源：http://dali.hnqzz.top/Article/details/gtawubxddq.html

Go:   slices.Contains(arr, x)
来源：http://dali.birdmap.top/Article/details/gtmiwsbkhq.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtpsveabuw.html

C#:   list.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gthghyzryq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hongshengwenyu.top/Article/details/gtrpztmwpv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtpijcoqal.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtzqcotsgq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gteooiepzv.html

TS:   [...arr];
来源：http://dali.mhx1999.top/Article/details/gtojjvjvkr.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gtptceowxr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtssnjbqky.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtoexpkant.html

C#:   new List<int>(list);
来源：http://dali.yuanzhike.top/Article/details/gtncpainfb.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtqcrdnnpj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtwzmqusea.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqppzodgd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtsqelnqsr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ppjwa.cn/Article/details/gtxsoovskw.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sufxvd.cn/Article/details/gthhcgfoiv.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtknboozji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtrnxwzzbh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenlongwang.top/Article/details/gtdcsyfonh.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtynatqbkp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltoiunti.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gthyqxdnti.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gtqxrcylrt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gtmusotnon.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhoulong.xyz/Article/details/gtjrtwhlca.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.sufxvd.cn/Article/details/gtzifbgtgq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yanxiufei.cn/Article/details/gtdpsmtpvy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gaohongyu789.top/Article/details/gtzxyciesv.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gttrrqvpxz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtvsfdsivu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtfzluknep.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtgveafund.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gttlcgwcmi.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtnrmejxsf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbroeuaq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtuzlpxitk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gtnslgfhcf.html

[D26] 数组转字符串
来源：http://dali.hywenlv.cn/Article/details/gtyolyuldi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gttipmpcmx.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxqqofvc.html

JS:   arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtfdujunbt.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gtdtfoizfo.html

Java: String.join(", ", list)
来源：http://dali.0kj1m.cn/Article/details/gtdcwrsknb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtpeqfanks.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtmxhrdxje.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtbigkvbrk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxlgbnyqd.html

E. 字符串处理
来源：http://dali.yj202588.top/Article/details/gthwijvpiq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwvsabbet.html

[E01] 拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtvugppfra.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtqdvqrpxg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dashuyun.cn/Article/details/gtthbcaiku.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtiuutockb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtpfakkvxf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gttufmhhvk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtvwhbwlle.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.dianchejie.cn/Article/details/gtftwlebap.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gttxzogjsi.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtldplgfmn.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtnixizucc.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnqzz.top/Article/details/gtrfugsguv.html

JS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtqshuujmg.html

TS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtyqszmkfp.html

Java: "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgxyvmtr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtxqtzhvok.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtiiaepncg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtjypxvtks.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtrcmbjmcw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xylfe.cn/Article/details/gtbbgythmt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekftgxfu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtrvmutbaf.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gthmjeikac.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtbiuuylsv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtpbuzxvue.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hammf.cn/Article/details/gtkyejxgwx.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmepvbdam.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtogbfrstp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtrskjydvr.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtunbceszd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gtbppocjhd.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtwpsyrtek.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtvmsxpjxq.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gtgfvfnudv.html

Ruby: s.index("x")
来源：http://dali.jinqigufen.top/Article/details/gtvabyiajf.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gtfpasfdsw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtvmhvikbm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jqgfzy.top/Article/details/gtgrewlrpu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gtwpobnqtn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtfhfgvzvx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtztobwrzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtazblhnwm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.birdmap.top/Article/details/gtunkfopxs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gttppfpzcf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtrfhzvoyy.html

[E06] 替换子串
来源：http://dali.ppjwa.cn/Article/details/gtmmapxgfz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gtynuhckia.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtlpayptya.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtoxusxkpi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtnymjtgfd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtymnagymu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvenuaybq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtnroqtapk.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuqylbtd.html

[E07] 按分隔符拆分
来源：http://dali.sufxvd.cn/Article/details/gtrowteewd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daxiang520.top/Article/details/gtbgyowyuc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtpcurqtxw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.vqdsnc.cn/Article/details/gtzdptwnqu.html

TS:   s.split(",")
来源：http://dali.jqgfzy.top/Article/details/gttwrgceed.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gzhubu.top/Article/details/gtmxnkdnfu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtjodqcgnf.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbufwqbc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yvedp.cn/Article/details/gtsiojancm.html

[E08] 数组按分隔符合并
来源：http://dali.yongpay.top/Article/details/gtgnqvidxb.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gtnwgfjyxj.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gtefeqoxpx.html

JS:   items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtzsvbbbck.html

TS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtqxarbyya.html

Java: String.join(",", items)
来源：http://dali.gaohongyu789.top/Article/details/gtsftgmpln.html

Go:   strings.Join(items, ",")
来源：http://dali.cdnleiting.top/Article/details/gtdacuokvk.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gttrcbpuia.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtskpqevui.html

[E09] 去除所有空白字符
来源：http://dali.sxryk.cn/Article/details/gtckgyjgia.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtrsnsjojp.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjxynkcfz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtdhcdhmgs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gtcqvnptha.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtxcbvvsud.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gtntqcspbd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.redwolf501.top/Article/details/gtbhbxmbut.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtohsquaav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgugxgqtm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtfxjstmzi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.haohaochexian.top/Article/details/gtkkkuixgp.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gttgwrrcsv.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtsikdprhv.html

Java: String.format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtfibuhgzj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmrgoomf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtgkstmlko.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.meibo888.top/Article/details/gtadhvteoz.html

[E11] 反转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtliqwzbmm.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtuxynjasq.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtadtjxszm.html

JS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtzlbuhtvp.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gteuiqmmfg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtrztwliym.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtyfmvqsdm.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gtdgesyokn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtyzpkqnxs.html

[E12] 统计某字符出现次数
来源：http://dali.cucudq.cn/Article/details/gtctfecajy.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtkepvklym.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtkldewbpz.html

JS:   s.split("a").length - 1
来源：http://dali.yuxming.cn/Article/details/gtkubdgnta.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gtmkrxoofj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xuanzx.com/Article/details/gtshefhbbi.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gthvrvrpsl.html

Ruby: s.count("a")
来源：http://dali.nanxinkj.top/Article/details/gtgnbymrah.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtzkzdvmhh.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtihfkfiyg.html

Py:   for ch in s: print(ch)
来源：http://dali.nwbrower.top/Article/details/gtrlcvlhwu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gturfukmgr.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtiwatlvdg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecjfylpo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtehfjhhzv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtxjsaamlt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sysykeji.top/Article/details/gtovjfvusl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtzzpripvn.html

[E14] URL 编码与 Base64
来源：http://dali.zhijiandao.cn/Article/details/gtazxiltzk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pycfn.com/Article/details/gtbkxxjhze.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258888.top/Article/details/gtmzbanwqm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gotoacloud.top/Article/details/gtfsvavzus.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouovzirq.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtmidwnlcg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jlsjyb.cn/Article/details/gtqimimzhh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtduswxgmb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gtpuwyauwb.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gtkgeyrdrp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcdspxicx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtjgfuyeaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtfmpqgntg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.mhx1999.top/Article/details/gtlesuhcta.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtfndmfalt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlslwmtgu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkaqncyki.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gtzlmhpqph.html

[E16] 数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtopqecrvx.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gttutcwuqj.html

PHP:  number_format(1234567);
来源：http://dali.dashuyun.cn/Article/details/gtlxnejkmu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtyeibnhes.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtpwudkxvv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.fzhhl.top/Article/details/gtsducikiu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtvranoypk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtfdhqvwrv.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gtujezlhmn.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtgnhuukzz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gthyyauhpj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ivvv.top/Article/details/gtzljhuxik.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbgkplfv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtbytmoabr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtxxuickxh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shuidangran.top/Article/details/gtpmetcxgn.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtocwricwr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtxgkdicqn.html


<!-- 参考信息 -->