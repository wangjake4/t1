代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gt2gpmybqzg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2xmjmjqac.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gt2fkepqegs.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2komdbhfw.html

Ruby: arr.index(x)
来源：http://dali.hnqzz.top/Article/details/gt2igkvdrgd.html

C#:   list.IndexOf(x);
来源：http://dali.kuanghao11.cn/Article/details/gt2bvpiuyra.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tian-w.cn/Article/details/gt2dagzlmhx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gt2rxsjicgl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.redwolf501.top/Article/details/gt2itwgrxxm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2zjvcmykr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gt2rgwhbwba.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyrsddzw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gt2ddsozfku.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gt2xwhahthg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2vgdtlndt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gt2mzxxxigl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbykznxg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2dlczzqxi.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2uuftstis.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2kmqkwyaw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eotjncjl.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pooxhchz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2qgcvkjdt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2tswjrjcb.html

[D15] 去重
来源：http://dali.tanke756.top/Article/details/gt2uvigihbu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.redwolf501.top/Article/details/gt2lzakibvf.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqvftfuu.html

JS:   [...new Set(arr)]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwbwenqt.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2shqidltf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gt2piwiappe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gt2yqwmuxxl.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aagcqixp.html

C#:   list.Distinct().ToList()
来源：http://dali.gogol.net.cn/Article/details/gt2zschunck.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2rfbzimkz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2lpuxufpq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hammf.cn/Article/details/gt2hiimfxik.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gt2spnhjacd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2wvnrkiba.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gt2zsmbamfy.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2fxpmzpdk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shuidangran.top/Article/details/gt2czgtdprh.html

C#:   list.Sum();  list.Average()
来源：http://dali.cucudq.cn/Article/details/gt2qklyhbco.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2yadcsemq.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gt2qvnjyiub.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2xdjtkxsx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gt2rvgzmbde.html

TS:   Math.max(...arr);
来源：http://dali.yj20258.top/Article/details/gt2gxbfuzrj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gt2xphbmqta.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ijotiyhw.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gt2sfmkqqym.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2qcooxujz.html

[D18] 扁平化嵌套数组
来源：http://dali.yongpay.top/Article/details/gt2dafmyumf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gt2rfbwszks.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gt2opjpczjj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gt2mxwavrei.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxdvmyox.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mapgbtpd.html

Go:   // 手写双层循环
来源：http://dali.hammf.cn/Article/details/gt2hahyspec.html

Ruby: nested.flatten
来源：http://dali.zhixingplan.top/Article/details/gt2ietidzqz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2rwuvzozn.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gt2vviojxnz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sufxvd.cn/Article/details/gt2mggsobjs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhengqikj.top/Article/details/gt2qxweaaaq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2pdmszech.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gt2cossyxhl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gt2rlcuzkrz.html

Go:   // 手写 map[string][]T
来源：http://dali.tanke756.top/Article/details/gt2oelllztj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gt2mtpuincd.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cucudq.cn/Article/details/gt2dhphfecq.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2tjagrydt.html

Py:   Counter(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2cnjvaqgf.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gt2svqsbmza.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2ulkgpsgd.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gt2driyqtdk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbnyrzrb.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2yerstjta.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2hnnwqjwq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigufen.top/Article/details/gt2zhqtjfwn.html

[D21] 判断是否包含某元素
来源：http://dali.tianlin.xyz/Article/details/gt2mitgopgr.html

Py:   x in arr
来源：http://dali.yj20258.top/Article/details/gt2mnraweje.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gt2tqlkvnyc.html

JS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2nchmyxgj.html

TS:   arr.includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2lhlygxhn.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2rkvctooa.html

Go:   slices.Contains(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2mrwdyspa.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2cozwmlda.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2jenbkoau.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dashuyun.cn/Article/details/gt2gcrkywhp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2lwsyhhja.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yongpay.top/Article/details/gt2lxqeyizp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2tgkqwojh.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gt2djczpsrr.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gt2icrdnsww.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gt2hzgapvgc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gt2ziraqomy.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gt2izheucgu.html

[D23] reduce 累积计算
来源：http://dali.dashuyun.cn/Article/details/gt2iugrjglw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cheryme.top/Article/details/gt2bqqoruxw.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilgqcabp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gt2zuiskprp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2bmurnupe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2rznibkzr.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gt2lwppstpl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gt2pvxcwpvj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfaqpfgc.html

[D24] 字典 / Map 基本操作
来源：http://dali.shuidangran.top/Article/details/gt2vnoctahf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gt2kqqczwjy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gt2zpwdhogu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gt2hnmymmyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2dweaibci.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2yqgxwdsm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuxming.cn/Article/details/gt2sykczsev.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2vcgmxmah.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gt2hqqaiblp.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gt2twbjqkrb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.316326.xyz/Article/details/gt2uieijgfd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psoossuw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gt2wxntydoj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cdnleiting.top/Article/details/gt2gkdxxdsv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2xsfshkal.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenlongwang.top/Article/details/gt2zblydxsz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gt2horqyatl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2dpkindcu.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gt2awokjzmq.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gt2yoagrvyi.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2humkoxak.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gt2crfloawh.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2xvtgdpui.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wapvijvf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2hzedtvfn.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wpdnorlj.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gt2baqjkphl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2niuobxhf.html

E. 字符串处理
来源：http://dali.dashuyun.cn/Article/details/gt2isipmdsb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2czibcvlc.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2yehaauok.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gt2gklbdkqa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gt2xywaurav.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2znwjutre.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gt2fwkwpgve.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gt2hbtozula.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gt2qeifbtjr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gt2gyjukowa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.c1oappe.top/Article/details/gt2dphhttiq.html

[E02] 重复字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2zaypjwli.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2rxcimcil.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gt2hdqwgwnr.html

JS:   "ab".repeat(3)
来源：http://dali.dianchejie.cn/Article/details/gt2aqikqfqt.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2hyeuplyb.html

Java: "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gt2rrgwmodo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj202588.top/Article/details/gt2lcyombrf.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkzgeale.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gt2xiocbuiu.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2kmivrolt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gt2slzsfhdh.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2aeghufsn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvdsiwsf.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2evnrwfny.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwgyioyh.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.meibo888.top/Article/details/gt2ciglmyaf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igyqhbsb.html

C#:   s.Substring(1, 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2kjlumihr.html

[E04] 查找子串位置
来源：http://dali.feifeiyinyue.top/Article/details/gt2mseetoem.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gt2fsynuwdt.html

PHP:  strpos($s, "x");
来源：http://dali.xinyue.icu/Article/details/gt2ndfoflxb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lomknpyw.html

TS:   s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tytcyrya.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zruqhrss.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gt2temwekab.html

Ruby: s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gt2nfnhqinf.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gt2rsydiwny.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ivvv.top/Article/details/gt2aeqnkcpo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gt2vhqtaede.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.9152youxi.cn/Article/details/gt2rrekeydt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gt2ohoiglkn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqcstvad.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2smjmpxnh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gt2kbmsbbxa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gt2grnkxrzh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqcjzfxn.html

[E06] 替换子串
来源：http://dali.jqgfzy.top/Article/details/gt2pjpruucx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ehwqpu.com/Article/details/gt2ggpwqukt.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vddcrbmx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhobkjic.html

TS:   s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gt2dmbisbbx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gt2dhwbuqxs.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gt2czmysjya.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.fzhhl.top/Article/details/gt2kxyfokru.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gt2jwwurzrc.html

[E07] 按分隔符拆分
来源：http://dali.iojbl.cn/Article/details/gt2ieqsvjjh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.iojbl.cn/Article/details/gt2ioryfqeu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2arjsxwmw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gt2opmpaidr.html

TS:   s.split(",")
来源：http://dali.dashuyun.cn/Article/details/gt2jjdwrqrz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2hqcmkhqy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gt2tqoyxuat.html

Ruby: s.split(",");  s.split
来源：http://dali.ivvv.top/Article/details/gt2zgwluoat.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2rhhweokx.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gt2vazxaakk.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gt2uzidheiv.html

PHP:  implode(",", $items);
来源：http://dali.gzhubu.top/Article/details/gt2pxfvqeid.html

JS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2insendie.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gt2revtxmyj.html

Java: String.join(",", items)
来源：http://dali.yj20258.top/Article/details/gt2mmwjupwi.html

Go:   strings.Join(items, ",")
来源：http://dali.jyoumei.cn/Article/details/gt2tlkigtkh.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiepnfqp.html

C#:   string.Join(",", items)
来源：http://dali.yonumen.top/Article/details/gt2ininvfpl.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2mpwvyszy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2zypibzsq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2suchsclr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gt2czsyordm.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yuanzhike.top/Article/details/gt2gbrgwiqq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gt2fkcybvfu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2rckkbsbh.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hammf.cn/Article/details/gt2nabadjmt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjcmcmwj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shzxlz.cn/Article/details/gt2qbhhvagx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2uypqoijm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhixingplan.top/Article/details/gt2zctnsdma.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gt2zjdryuys.html

TS:   "7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gt2limuryhy.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gt2ofyziixs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gt2vfddgruj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gt2rehnvghi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2eouuhywm.html

[E11] 反转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2iuqgtnem.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2davufplb.html

PHP:  strrev($s);
来源：http://dali.nwbrower.top/Article/details/gt2fungpngl.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2nlylvhvb.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2cgzocifn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yongpay.top/Article/details/gt2bxmacoqn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2jpxlsikv.html

Ruby: s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgbicxji.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2xtdlfzey.html

[E12] 统计某字符出现次数
来源：http://dali.cashguo.top/Article/details/gt2zmoojzru.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2krlzpfar.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gt2deiygtgq.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2aefxnvjj.html

TS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2ibrbcfvi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.c1oappe.top/Article/details/gt2ijatpbgi.html

Go:   strings.Count(s, "a")
来源：http://dali.yueranfly.top/Article/details/gt2fvhykkqu.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2wruyvoqq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2qeidoysv.html

[E13] 逐字符遍历
来源：http://dali.chenlongwang.top/Article/details/gt2rrwbbxly.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gt2exefdfhx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gt2fxrtfgap.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulrcwiad.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2flqwixfr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2xlfmcjrn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnmdvtig.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gt2pgjcoxtc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jqgfzy.top/Article/details/gt2mmofjznj.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2syjwgxyw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yj202588.top/Article/details/gt2yofawhce.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gt2qwmxjnwk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwjjpagl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yvedp.cn/Article/details/gt2madgzrjx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2opfeaxxv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gt2pokgmuux.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gt2fnudvmht.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2rsilyjtz.html

[E15] HTML 转义 / 反转义
来源：http://dali.sufxvd.cn/Article/details/gt2kyjamfjt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gt2zriynwlz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gt2nlsipzhd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gt2hsilckpu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2jvcsgmnl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.mhx1999.top/Article/details/gt2mutfluyo.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwbfqodu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zycfv.cn/Article/details/gt2zpnxglyp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2jbavlllg.html

[E16] 数字千分位
来源：http://dali.cheryme.top/Article/details/gt2bcaecyqn.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gt2bozdfcdk.html

PHP:  number_format(1234567);
来源：http://dali.yuxming.cn/Article/details/gt2atlbeigl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gt2xykmkflc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2cvxlckqp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gt2tnqcnays.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2iadopqdi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2vtyxejob.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gt2umxcfkvx.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gt2umwrjxkr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ybcxt.top/Article/details/gt2fzirjwsz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gt2hedbymfi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ezzegoko.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2umhfmpxy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.fengsongda.top/Article/details/gt2iqdymvfj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2ewqvwwmx.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2yajkzmvn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gt2yizmzxoe.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gt2hmfujtax.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.haohaochexian.top/Article/details/gt2fkgbzhmd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogeqybih.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2zyufgfaq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2nxqyuzun.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoodsmti.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2fynfscse.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yangfankeji.com/Article/details/gt2rtahjodj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.dashuyun.cn/Article/details/gt2dpwxvipp.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gt2baqpqdxp.html

Py:   s.splitlines()
来源：http://dali.daxiang520.top/Article/details/gt2qjgdrxjk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjdwiyic.html


<!-- 参考信息 -->