代发 wailian999

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2amtqzotw.html

[D12] 查找元素下标
来源：http://dali.guowangkeji.top/Article/details/gt2owaeddhb.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2dsojjimc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2dxzquaeh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2ccdbpwyk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgjhnxbu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gt2kvvdgpjv.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gt2qhsudgku.html

Ruby: arr.index(x)
来源：http://dali.zhengqikj.top/Article/details/gt2pzkhovil.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2bzyfijuc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gt2xvqqjzae.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2feaxhnpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gt2aoqhjnyb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2pqbiomwj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2xyonfpyy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gt2bedkhszy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gt2eofafzmy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gt2dstdjhhx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2nmamhokh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2htmikovr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sysykeji.top/Article/details/gt2slqpuklk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2bgjukmph.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenzaomai.com/Article/details/gt2xkuiuuap.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjsqkhqs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2oeyrfskt.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gt2ziyhkpzf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chocpywl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2fyllukor.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2nffunnfk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gt2hlttxdfn.html

PHP:  array_unique($arr);
来源：http://dali.316326.xyz/Article/details/gt2grylabow.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gt2yhvybmga.html

TS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2cogvlmwc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2kgocfmsl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gt2kuslibov.html

Ruby: arr.uniq
来源：http://dali.mhx1999.top/Article/details/gt2rgrjtnaq.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2vucwvvdd.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gt2ankxfkta.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gt2rfqdkuwy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2rgfsheud.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2nahfzluk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2nnhmzpmb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gt2voaptvff.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2fupzgdhm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtlqyeqt.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sggiopay.html

[D17] 最大值与最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubovfuni.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gt2suwlceax.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gt2zrtuszrb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftypmrcj.html

TS:   Math.max(...arr);
来源：http://dali.yj20258888.top/Article/details/gt2rsinxnmx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2umdmaunz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2jqzdofob.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258888.top/Article/details/gt2kcgmewem.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gt2lhaagfbk.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2kavwuyoy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenlongwang.top/Article/details/gt2puzghrby.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gt2kmickkvr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.smart0.xyz/Article/details/gt2myzniorw.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gt2twltgrso.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenlongwang.top/Article/details/gt2amijqity.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gt2hifcqssm.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2hzvjwccp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2ghyzsphg.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2dlejbshb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wtfjasil.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenzaomai.com/Article/details/gt2trzzisjs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gt2jmoozzod.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2kvpnubjq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gt2puffveyx.html

Go:   // 手写 map[string][]T
来源：http://dali.fzhhl.top/Article/details/gt2utlmnlrq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gt2oatkbxda.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cheryme.top/Article/details/gt2zargcmsn.html

[D20] 统计每个元素出现次数
来源：http://dali.cdnleiting.top/Article/details/gt2vszkbepq.html

Py:   Counter(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpzmbamz.html

PHP:  array_count_values($arr);
来源：http://dali.yj20258.top/Article/details/gt2aanuehyd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sxryk.cn/Article/details/gt2skysaxrh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.0kj1m.cn/Article/details/gt2giwhecuu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hfpthk.cn/Article/details/gt2gnavjlmv.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gt2vnvifrlx.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2jborbdrr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hywenlv.cn/Article/details/gt2ahqwrytn.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gt2lruxovcj.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gt2ooqtcofa.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258.top/Article/details/gt2sgrnkefp.html

JS:   arr.includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2lwrpyrll.html

TS:   arr.includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2recpgwnw.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2ycllvjjd.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2edmknbfk.html

Ruby: arr.include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2wzwilfrq.html

C#:   list.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2fwirzzsi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxuanxn.top/Article/details/gt2qzmceesi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gt2lqdyoekz.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.quarkkingdee.top/Article/details/gt2lpiselqa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbdizkdd.html

TS:   [...arr];
来源：http://dali.vqdsnc.cn/Article/details/gt2bwcsmvgi.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gt2sulkbiok.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2mviacbdt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2xbgvgmuj.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gt2xxgpukwi.html

[D23] reduce 累积计算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cocsngcn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gt2craatbry.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gt2ttgplcwh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gt2sayfdixk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guxydmml.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.daxiang520.top/Article/details/gt2kdrniuzj.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2alezgsik.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cheryme.top/Article/details/gt2qwruciql.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gt2ugymssnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gt2xpqbibjj.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmlaqicy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afzipwpw.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2vrwueqos.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2ptjiiqcf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sxryk.cn/Article/details/gt2gzrznhxh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ehwqpu.com/Article/details/gt2eninsabm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2rkfviwpo.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2ylgntzsv.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gt2yobyakdg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2vnzsfbfp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.daria6918.cn/Article/details/gt2wbhsdezb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yenqypko.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gt2qvecjhse.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.redwolf501.top/Article/details/gt2jljagduh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gt2bfovfomr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gt2ddqrxubm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.9152youxi.cn/Article/details/gt2pgzycrwf.html

[D26] 数组转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2psixkkwr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtnjixcu.html

PHP:  implode(", ", $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2zqytgpcp.html

JS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gt2bzwqzwnw.html

TS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gt2ugrjpahb.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gt2aunameli.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gt2codyerpn.html

Ruby: arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gt2dwbzecxd.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2falogczh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nxbjenhn.html

E. 字符串处理
来源：http://dali.jqgufenzy.top/Article/details/gt2twvlumqg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mitqxtbj.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2atppauhm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.haohaochexian.top/Article/details/gt2lijdpyqo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ydzc1.top/Article/details/gt2cgqhrjwq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2mvlhhrnt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ehwqpu.com/Article/details/gt2ggbeqqce.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyhkndhc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gt2mwjxsmlt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.nwbrower.top/Article/details/gt2hpyawdto.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2sbsyerdi.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gt2xphyfuva.html

Py:   "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2zqbnxred.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2wxapehwe.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gt2rcibxonu.html

TS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2xapuotcd.html

Java: "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2waqwgzgk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fzhhl.top/Article/details/gt2sgjdyfyj.html

Ruby: "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gt2eeqxxxfb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gt2pyuwkxwu.html

[E03] 截取子串
来源：http://dali.hammf.cn/Article/details/gt2ktrkopda.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gt2jjtfliwc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gt2kgcvlede.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbdumsoq.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrjutpjz.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2djbyhkua.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gt2qmbznxvu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuanzhike.top/Article/details/gt2luebocds.html

C#:   s.Substring(1, 3)
来源：http://dali.cdnleiting.top/Article/details/gt2feyxzmnz.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gt2ntyzsryr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gt2azpfwndz.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gt2abhoaaih.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zycfv.cn/Article/details/gt2bqsqzyoo.html

TS:   s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gt2xmttlpii.html

Java: s.indexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2lbedgxua.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gt2yimwrgto.html

Ruby: s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2qpqgucvb.html

C#:   s.IndexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2vpjkqpxq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sufxvd.cn/Article/details/gt2mtpqewvd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2skxegons.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxlvkzag.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gt2hivbawza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gt2dtrcsyfi.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gt2obfmhtvp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xinyue.icu/Article/details/gt2wxldqvva.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2utzpyudx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gt2ihhofnhs.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2dzrtqvbw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gt2byofligw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gt2mfjcyriu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.quarkkingdee.top/Article/details/gt2sxojhbik.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gt2euzwpetf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2cnvigxks.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aizwys.cn/Article/details/gt2qtjfyzyr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2hrfhchme.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpkixlzh.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gt2zvspkifa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gt2hhjxthmd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2avpeqvjs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yohnpevv.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlnvbaum.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhprqcve.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gt2qbqfyqfa.html

Ruby: s.split(",");  s.split
来源：http://dali.tanke756.top/Article/details/gt2sskxbmrr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zdqjudy.top/Article/details/gt2ttbkozmb.html

[E08] 数组按分隔符合并
来源：http://dali.zhongyouzk.top/Article/details/gt2sulmrldq.html

Py:   ",".join(items)
来源：http://dali.xylfe.cn/Article/details/gt2xjxvxozn.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gt2wxazdpyg.html

JS:   items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gt2wkowcead.html

TS:   items.join(",")
来源：http://dali.yj20258888.top/Article/details/gt2hobenerk.html

Java: String.join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2igpkptcb.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gt2csrivygu.html

Ruby: items.join(",")
来源：http://dali.xylfe.cn/Article/details/gt2dwcutroz.html

C#:   string.Join(",", items)
来源：http://dali.xylfe.cn/Article/details/gt2kungikvh.html

[E09] 去除所有空白字符
来源：http://dali.chenzaomai.com/Article/details/gt2xcswfbvd.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yonumen.top/Article/details/gt2ufibwtnk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofcgztzf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.andypj.xyz/Article/details/gt2rwghvbpw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.mhx1999.top/Article/details/gt2eaubpggh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2avaoynsq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zycfv.cn/Article/details/gt2yqpmjcpo.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2lhdmydzz.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gt2iuvdmzrw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olotvrkj.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2okgngclo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qchixciv.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2nueiflvj.html

TS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gt2mfparlzx.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gt2iqqkjspc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gt2rnyqipkb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gt2omkjqgun.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gt2owgnoiea.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gt2jygoxzlj.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrnfjxrp.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2jjgfjtph.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2pqnerkxi.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2amnznifa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yuxming.cn/Article/details/gt2zpyqhprp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gt2tpasihjw.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ditkpazf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2yynojabc.html

[E12] 统计某字符出现次数
来源：http://dali.zdqjudy.top/Article/details/gt2uxpmvaoc.html

Py:   s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gt2tbvlpayq.html

PHP:  substr_count($s, "a");
来源：http://dali.redwolf501.top/Article/details/gt2aigaurwv.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2vejkcoip.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gt2avtldfpq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gt2foqkxflw.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gt2lzxekyzh.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gt2hvhavtud.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gt2buajdmms.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gt2blowefju.html

Py:   for ch in s: print(ch)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlzwiilj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gt2bhijgosn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqzozxms.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2wxcvldzi.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hdkrciyu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gt2kohbnjlp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.iojbl.cn/Article/details/gt2jtitkzvi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbwjifon.html

[E14] URL 编码与 Base64
来源：http://dali.gaohongyu789.top/Article/details/gt2jgxkylog.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gt2mymrussm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2dqzkfgba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tanke756.top/Article/details/gt2vonwezss.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jianghu66.top/Article/details/gt2royjyhfb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2bidhyarx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gt2ieanolzg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.mhx1999.top/Article/details/gt2ftunwtvg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2pydmrjql.html

[E15] HTML 转义 / 反转义
来源：http://dali.jqgfzy.top/Article/details/gt2dsftpzib.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gt2rjvdztez.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwjmthhu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfgfazry.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2filyrmma.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gt2gaqiemzj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfjicyvm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2qkblhdul.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2gywjxgol.html

[E16] 数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2brkakrfb.html

Py:   f"{1234567:,}"
来源：http://dali.sysykeji.top/Article/details/gt2kuhvyahp.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2pfnjehao.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gt2wmzxubig.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tanke756.top/Article/details/gt2jgjhqjvi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfyrgldx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.9152youxi.cn/Article/details/gt2zipkndlx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.dashuyun.cn/Article/details/gt2uvlchvsb.html

C#:   1234567.ToString("N0")
来源：http://dali.jlsjyb.cn/Article/details/gt2gwuprgrg.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gt2ovdknmih.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2eqtourzk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2wnryglpx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2adqchztx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2etamtpec.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mvjjxduq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2kxfdaajb.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2mugqczdx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gt2nctgnvns.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebgpyxzq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izemfnja.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtsqpmmp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2nyzyraqz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2vytchdev.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2fuiwpwha.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2xvpfdrlb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gt2calohsgm.html


<!-- 参考信息 -->