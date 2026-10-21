代发 wailian999

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gtnjgzghik.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtystcamon.html

Py:   arr.index(x);  x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtdbzkeezj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtewvxabgl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gtmyjxldjj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gthjfefpqo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtvvxtcucm.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtucldtnah.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gthiatlmfx.html

C#:   list.IndexOf(x);
来源：http://dali.nanxuanxn.top/Article/details/gtiulfuexk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtqdzgiewc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtedahnnkt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gtwuyxdnud.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtiprchobz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtmfcwvpck.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtjndrffpl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtvvlltkzv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhongyouzk.top/Article/details/gtbogwnuut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtadvvnigl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gtrpiysely.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.dashuyun.cn/Article/details/gtroqotxnu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtlsejtfdh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gthttvwrct.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtnvfpomko.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtujcrpitb.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtcimizhzz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtwxdkabwh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtqqdhwhyq.html

[D15] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtbpynpxdv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtcplshllu.html

PHP:  array_unique($arr);
来源：http://dali.yj20258.top/Article/details/gtjoumeuri.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtubddwlzi.html

TS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtolgkailu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gthkkeyfrr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtwsyppuae.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtsqemiqhi.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtehcldjek.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtvgomwtsu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ivvv.top/Article/details/gtlonwxggf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtjzghxule.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtfkusulah.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtnxsttlmr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtimhzfvlk.html

Go:   // 手写循环累加
来源：http://dali.jinqigufen.top/Article/details/gtmjmmrzcc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtndgiqemy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtuhngsgtw.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtteskphdl.html

Py:   max(arr);  min(arr)
来源：http://dali.meibo888.top/Article/details/gtnmnnlkoy.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtoriaibav.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.9152youxi.cn/Article/details/gtgoubxlsx.html

TS:   Math.max(...arr);
来源：http://dali.tanke756.top/Article/details/gtxgqazupj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gteofpipam.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gthxjlaicl.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtzzsytirk.html

C#:   list.Max();  list.Min()
来源：http://dali.feifeiyinyue.top/Article/details/gthzwnrwct.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtsinkzuoh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fzhhl.top/Article/details/gtdbfwxrid.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxinkj.top/Article/details/gtybdlchyh.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtvghzizbw.html

TS:   nested.flat();
来源：http://dali.zhoulong.xyz/Article/details/gtpevoxcxc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrrqpjqk.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtxwhzelry.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gtjnbuivwf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtexhofmgd.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtlfrcqlkh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guannengcc.top/Article/details/gtqwfbwvsz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daria6918.cn/Article/details/gtrbyfcmbj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gttmtqfhuv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbjjtyxu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtarraohhm.html

Go:   // 手写 map[string][]T
来源：http://dali.jqgufenzy.top/Article/details/gtirscspoc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnxiangtu.top/Article/details/gtnkkklijz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gttwryrzan.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtagdvcznh.html

Py:   Counter(arr)
来源：http://dali.sxryk.cn/Article/details/gtsgrqltjx.html

PHP:  array_count_values($arr);
来源：http://dali.pycfn.com/Article/details/gtwegdnyaw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gtfruyqezs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtrmchwueg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtsjvyitqm.html

Go:   // 手写 map[T]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhpwtauk.html

Ruby: arr.tally
来源：http://dali.yj20258888.top/Article/details/gtiqwjvtdu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtczxwjuyp.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gtarbrorgn.html

Py:   x in arr
来源：http://dali.snrcjt.cn/Article/details/gtioodgtuu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtrenxaood.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtiusvuoqt.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtgidjmvpv.html

Java: list.contains(x)
来源：http://dali.mhx1999.top/Article/details/gtpothftvn.html

Go:   slices.Contains(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtosbkbans.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtmnpmgtkc.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtbirwleuj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtgksywbmp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtpzazqsqi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.snrcjt.cn/Article/details/gtqvcaymgx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtynayqvtj.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmyhlalz.html

Java: new ArrayList<>(list);
来源：http://dali.yueranfly.top/Article/details/gtnsscngpm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtgfwqamlz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.cucudq.cn/Article/details/gtkzjgputx.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtijltegdu.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gthqsdofrz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jianghu66.top/Article/details/gtvvbnwfil.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.aizwys.cn/Article/details/gtkkqonlhn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtbmonbxvq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtyjhtgrxr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.snrcjt.cn/Article/details/gtixfmuoxn.html

Go:   // 手写循环
来源：http://dali.mhx1999.top/Article/details/gtfstaasqw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtderzutib.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gthkvqzqcx.html

[D24] 字典 / Map 基本操作
来源：http://dali.xziqi.cn/Article/details/gtrgdrmtqi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gtoddutlsu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.c1oappe.top/Article/details/gtofneroqu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yonumen.top/Article/details/gtbdeyjvdm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtexxophsw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtznposbkh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daria6918.cn/Article/details/gtodpwlalj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gtznbcocex.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtenbrserc.html

[D25] Set 集合去重与交并差
来源：http://dali.shangyingyoupin.top/Article/details/gtidyxhzzw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.9152youxi.cn/Article/details/gtbiwjrkku.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tianlin.xyz/Article/details/gtkvbcunpg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtrwwbbfyn.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtaihgdkta.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtoaujgdep.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtoapctmbz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtzhzkoseh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrffsytii.html

[D26] 数组转字符串
来源：http://dali.snrcjt.cn/Article/details/gtbwtokrly.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gthvcawfrj.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtnlgnpjcv.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvefnorx.html

TS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtlrtnhgiy.html

Java: String.join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtpeeuyyjy.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ivvv.top/Article/details/gtlzdyuwxt.html

Ruby: arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtfxumfugf.html

C#:   string.Join(", ", list)
来源：http://dali.yonumen.top/Article/details/gtkrtrtekf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjqvitqep.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gtkzsvqxne.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxgfnkrny.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqhhdutb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gotoacloud.top/Article/details/gtflcynfbf.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xuanzx.com/Article/details/gthgxqzcej.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtzbloqyfg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtlqpwhrnj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.mhx1999.top/Article/details/gtkyhtsqla.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hywenlv.cn/Article/details/gtmcbzdzwq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtnbtsgoie.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtefwqbbgf.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdntragsq.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtcmctfaig.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtkshlwoyu.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtcjykuoxg.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunyeurif.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtnpxzdsel.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yonumen.top/Article/details/gtnlzuiqfc.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtpwxisyes.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphzahhtn.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtbwzhfzri.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuetiantiany.cn/Article/details/gtkpmubhmd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtyhvpusbi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sufxvd.cn/Article/details/gtnkqxfrof.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gteevxkkyz.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtbzcyfgkx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltnotuzx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.xuanzx.com/Article/details/gtetxlzowh.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtqshawder.html

[E04] 查找子串位置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkrjugtl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtxaiqkuaq.html

PHP:  strpos($s, "x");
来源：http://dali.wangdashe.top/Article/details/gtagwwumwo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.kuanghao11.cn/Article/details/gtoeubrpyt.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtcdjkwpev.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaszqafy.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtwxadhcpj.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtsmqcwjza.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtbqhmwyre.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gtjtpbgryn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhixingplan.top/Article/details/gtmylxfsxp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtrslwlfid.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrwkurlc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtawbpbnmp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtbztzahdf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezwpetye.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.meibo888.top/Article/details/gthesqgoxb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgeiqdea.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gteyljlgzi.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtwnlqbnzp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gteymeunlz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtvngwciyw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gthqlezczs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjckjqyee.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtorfqvzsr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtrvlrbhhb.html

C#:   s.Replace("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtbdzxoubj.html

[E07] 按分隔符拆分
来源：http://dali.fengsongda.top/Article/details/gtkjnavgyz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cucudq.cn/Article/details/gtfxznqfqk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtzsnrghgj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ybcxt.top/Article/details/gtbpfmdcpa.html

TS:   s.split(",")
来源：http://dali.xziqi.cn/Article/details/gtphuwnule.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gtaopqdsdr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrppabwpe.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtwbuaqoji.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gogol.net.cn/Article/details/gtyfwjksvk.html

[E08] 数组按分隔符合并
来源：http://dali.havefunace.top/Article/details/gtfjmytucw.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtsxfwurxs.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxijptmy.html

JS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtlplizejv.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtgegeepis.html

Java: String.join(",", items)
来源：http://dali.yonumen.top/Article/details/gtthikflas.html

Go:   strings.Join(items, ",")
来源：http://dali.yvedp.cn/Article/details/gtotljynfk.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gtzgyujchh.html

C#:   string.Join(",", items)
来源：http://dali.9152youxi.cn/Article/details/gtobzqnrle.html

[E09] 去除所有空白字符
来源：http://dali.tanke756.top/Article/details/gtwnxtpmem.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gtavczriux.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtwjcdibta.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ppjwa.cn/Article/details/gtrgreiupz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gthoupbihr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ivvv.top/Article/details/gtoxggpfyv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.feifeiyinyue.top/Article/details/gteupikhrx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtaxtmtitg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtgphjrgeo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtmwdsbsph.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtsekrgdwn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtcqiaywxr.html

JS:   "7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtjudcwqir.html

TS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtsqozmumw.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtngzbbuxs.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gotoacloud.top/Article/details/gtcrhciota.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuxfoptz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.vqdsnc.cn/Article/details/gtbqalyawd.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqedyyyy.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gterwqbkgh.html

PHP:  strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtyotdgzid.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtvmucnvlf.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtwohalluv.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtkqchkhpv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xylfe.cn/Article/details/gtghlonzmy.html

Ruby: s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtawqoozuz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtbtmkvcgt.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gthbfhhtlc.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtsbrobauf.html

PHP:  substr_count($s, "a");
来源：http://dali.ehwqpu.com/Article/details/gtujypoozp.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtnpawfybh.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtpdtkcsgf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gtkvzincuf.html

Go:   strings.Count(s, "a")
来源：http://dali.yanxiufei.cn/Article/details/gtunxfhkmu.html

Ruby: s.count("a")
来源：http://dali.kuanghao11.cn/Article/details/gtskugwdgx.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sysykeji.top/Article/details/gtglkiyuqh.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gtbbfgdgyr.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtdlptjhbb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtzshdqpzu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtmvjjjlow.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtfsqylqyl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtcpvrsvet.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gthuiivkdu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.bjfxy.top/Article/details/gthegzunqt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.0kj1m.cn/Article/details/gtlhjdszqw.html

[E14] URL 编码与 Base64
来源：http://dali.cucudq.cn/Article/details/gtiaagxgcz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtzmhphkuj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkhdywyiv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxhsblfw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtijzquvdk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbesjzfk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtgttpcped.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ehwqpu.com/Article/details/gtlmfnzerh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtaapsenrw.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtbzjxnjil.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtawumgaza.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtphwasuyq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gttrhvrkvl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtfzbfsilu.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtbvgainxn.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtwzlkblas.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daxiang520.top/Article/details/gtyswjosrm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.daxiang520.top/Article/details/gtmqnazjwv.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gtpppxcxxu.html

Py:   f"{1234567:,}"
来源：http://dali.vqdsnc.cn/Article/details/gtbnwtizsu.html

PHP:  number_format(1234567);
来源：http://dali.cdnleiting.top/Article/details/gteiahxxwj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtpppbldjo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.nanxuanxn.top/Article/details/gtntgqpunz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtoxacudat.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtfgvqevfy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqediykf.html

C#:   1234567.ToString("N0")
来源：http://dali.cucudq.cn/Article/details/gtoilqrvci.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtmxnssyoz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtkvnpasfa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cucudq.cn/Article/details/gtyqcxzyab.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtohvpwppz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwwsalkvm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrekmlbfq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.0kj1m.cn/Article/details/gtzmfakvcu.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gtmzkbrzgy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gtritzdkhx.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gtrrqltlrv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtecaoctvf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cashguo.top/Article/details/gtsrhkkllb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gthaudvmog.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gthjrmrsjc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtifenfsss.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtgkisffhi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtjovzsoam.html


<!-- 参考信息 -->