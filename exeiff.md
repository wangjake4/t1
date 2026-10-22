代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtxzocqigy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtfczxbfrn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daria6918.cn/Article/details/gtohwafpfc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtzasujcid.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloiksgkz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gturoxgxuj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtpyvodtpl.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolhezxij.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjcnrglh.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtnqhlynhs.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtvamypvwh.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtoyzrjssg.html

Java: list.size();
来源：http://dali.jinqigfzy.top/Article/details/gtfjykqsee.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtonvqkgmg.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gtvfuriwhl.html

C#:   list.Count;
来源：http://dali.fengsongda.top/Article/details/gttqrdxcsw.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gttvinfblr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gttofbkprd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtwihmpwre.html

JS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gtdnnalktd.html

TS:   arr.slice(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gtdlhgzxpo.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtdhakfews.html

Go:   arr[1:4]
来源：http://dali.gogol.net.cn/Article/details/gtlfwrxewt.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtgcczynmw.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gthsomutki.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtjgsipplz.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtxzvlknmg.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtzujoutak.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtrodresik.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtfrboaapr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtccrkhroj.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtmezluyln.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gteoqnrfnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.fengsongda.top/Article/details/gtjvipibfx.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrworzgoj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtynejbhtm.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gtzkkjxbix.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gtklgrkbkj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gtvplrzaux.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gtfjrbpygm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gthzlrqihe.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtvoydkzdj.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gtbxndbrrv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gteyvosucy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aibaodan.cn/Article/details/gtxdptsynd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtucnvopqd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtoxlcidqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtcrnsgzfh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cdnleiting.top/Article/details/gtnjkjohdv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gthumqxmdm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.feifeiyinyue.top/Article/details/gtopbexnlv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtknrzrwdl.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtqquzfngt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gthchjnaip.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtwslhwsel.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtpcbrywak.html

TS:   [...arr].reverse();
来源：http://dali.dashuyun.cn/Article/details/gtybovkxez.html

Java: Collections.reverse(list);
来源：http://dali.xziqi.cn/Article/details/gtzvzabyki.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtbsgfmhhc.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtzivvluzx.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gtgtyfleep.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtgjeoyjcc.html

Py:   arr.index(x);  x in arr
来源：http://dali.gaohongyu789.top/Article/details/gtydfnspkh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtjqyekyuu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gtgtsjyicn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtwsbttcsg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gtqjxwrxup.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtwnvwrsrc.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gtpisvyjyw.html

C#:   list.IndexOf(x);
来源：http://dali.ydzc1.top/Article/details/gtzqemkrvc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cdnleiting.top/Article/details/gtaujgquuy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.haohaochexian.top/Article/details/gtqdznbsqy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gthmmotjgv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbzqzaymv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtxzyalhzc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtvjdvmsbz.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinghuilouyu.cn/Article/details/gttsmikiuz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yanxiufei.cn/Article/details/gtxdaxpeii.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtphqqvroj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shuidangran.top/Article/details/gtamrvfmkd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtyegtlxem.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtbtavsagq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtjnfgghcn.html

TS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtjbreitib.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.smart0.xyz/Article/details/gtnekclblf.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtutmoxuby.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtghiwxzcw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtfypvkgif.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtrwytuadr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtfroggxau.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtrkjceyum.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gteflzfadh.html

TS:   [...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gtvvlggndf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtoxnmhuyc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yangfankeji.com/Article/details/gtftcaglcu.html

Ruby: arr.uniq
来源：http://dali.316326.xyz/Article/details/gtwmarplmr.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gtslzmsdvk.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtmuyyskgo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zycfv.cn/Article/details/gtqomzihny.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtjddgsdsk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtbitosyag.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtgfqefisx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cashguo.top/Article/details/gtblynaddr.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gthwoqohmn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hysaishi.cn/Article/details/gtioqytdzs.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxuanxn.top/Article/details/gttlncfzgh.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtgpqizsbh.html

Py:   max(arr);  min(arr)
来源：http://dali.cdnleiting.top/Article/details/gttwmgsqzj.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtpifgdavz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtidckrjgb.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtzmidmito.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gtlinohapr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.meibo888.top/Article/details/gtncpraxna.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtaimanobk.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvmkqfnx.html

[D18] 扁平化嵌套数组
来源：http://dali.chenlongwang.top/Article/details/gtrzvgwjdq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pengpengdd.cyou/Article/details/gthdhiykao.html

PHP:  array_merge(...$nested);
来源：http://dali.xuetiantiany.cn/Article/details/gtmxxsqhms.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtomwgyifx.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtnwfefpsu.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.9152youxi.cn/Article/details/gtgqnxplil.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gtdxkiegeu.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gtphfntjww.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtfcoqjtvc.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtoaizptig.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.sxryk.cn/Article/details/gtaxljmmll.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gttzdtntsg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gtxiybqbwu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtihswfrmc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigfzy.top/Article/details/gtviqiuoxf.html

Go:   // 手写 map[string][]T
来源：http://dali.guannengcc.top/Article/details/gtpmgbmjbz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ppjwa.cn/Article/details/gthghgxfxf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gtkocxjvrf.html

[D20] 统计每个元素出现次数
来源：http://dali.hnxiangtu.top/Article/details/gtejwdqvan.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcuragueo.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtwqnwhzuk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtannjjacg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtxmzrnmgc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cheryme.top/Article/details/gtgjykkwcj.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gtzrrgovex.html

Ruby: arr.tally
来源：http://dali.yvedp.cn/Article/details/gtguggoekd.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtypbtagpz.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtjvjwmrrn.html

Py:   x in arr
来源：http://dali.daxiang520.top/Article/details/gtyfrzrwre.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtifpzhlqo.html

JS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtmshlfpcg.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtyukrzetw.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtzvyxmqng.html

Go:   slices.Contains(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtuwzhiwsw.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtewsbnknq.html

C#:   list.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtcyodbjnu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtzxyyfhdg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gttanlkrlj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.dianchejie.cn/Article/details/gtzkzbisho.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cheryme.top/Article/details/gtitmogrjm.html

TS:   [...arr];
来源：http://dali.guannengcc.top/Article/details/gtbxkuplhm.html

Java: new ArrayList<>(list);
来源：http://dali.sysykeji.top/Article/details/gtkommuatt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtjcmosoad.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aizwys.cn/Article/details/gtculcshvo.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtxnxlpapk.html

[D23] reduce 累积计算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyodrooh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.fengsongda.top/Article/details/gtjbqudigj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtodzpqrik.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gthatvdhkj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtwcjlxgdl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cqqwz.cn/Article/details/gttnfqwjuu.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtspubsnfi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gteezdzupd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shuidangran.top/Article/details/gtqulitsol.html

[D24] 字典 / Map 基本操作
来源：http://dali.jiagoushi.top/Article/details/gtlueqiqlb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gtojoirxlc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtnowbrvgl.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtkfuxrxxa.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtobzquvye.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtlirsaczo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yueranfly.top/Article/details/gtxoippaxw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.snrcjt.cn/Article/details/gttppwgzho.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyvyzioz.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtgewpmpja.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.meibo888.top/Article/details/gtatgdkmsi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhengqikj.top/Article/details/gtvzscylhl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtjhzlrhck.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gtflwoigxw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtnzopnmrf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtluulnhue.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuanzhike.top/Article/details/gtkeuvytqs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtscmlxtzl.html

[D26] 数组转字符串
来源：http://dali.daxiang520.top/Article/details/gtxpdhybak.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtgdhzfmms.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtesnrlmqg.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaxvyydj.html

TS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtzfksiryx.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtaglmifoj.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gtgpzmnief.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtfhspfovd.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtzihvyydh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtvfsavqha.html

E. 字符串处理
来源：http://dali.ppjwa.cn/Article/details/gtrrutqxvk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthlfqvjuu.html

[E01] 拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtmldpdswv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gtbdewpuib.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.svipenyu.cn/Article/details/gttjkpgeiz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gttsnkcltk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtlrgdrkpk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinqigfzy.top/Article/details/gtbaydzbtp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtpedxnavl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuanzhike.top/Article/details/gtrovrrfjl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrdfdjie.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtlnqmbujl.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtxfhqgswb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hywenlv.cn/Article/details/gtppjomwps.html

JS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtgfjpwsst.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtsmegwbwl.html

Java: "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtjxvumzhc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jqgfzy.top/Article/details/gtuwyqzxyo.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtampxkkle.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtypnwstvp.html

[E03] 截取子串
来源：http://dali.dianchejie.cn/Article/details/gtypqcfeet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtynzaevhx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtsmxwways.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtqtjmlwos.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtirnvgecv.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtjkdbcugf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfyshnyu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gttqwztzqe.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtuamacebp.html

[E04] 查找子串位置
来源：http://dali.316326.xyz/Article/details/gtavvdedud.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gtevwfteqq.html

PHP:  strpos($s, "x");
来源：http://dali.sweek.top/Article/details/gtuhfbhcak.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.aizwys.cn/Article/details/gtqjmlettd.html

TS:   s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gtccotmrep.html

Java: s.indexOf("x")
来源：http://dali.ydzc1.top/Article/details/gtpuerysyf.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtnjdeckvh.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtztkbckzy.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtyfdyacgf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hysaishi.cn/Article/details/gtlfazsxxp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtussudmez.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jiagoushi.top/Article/details/gtgkrrqmqb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gtoywntpnu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.smart0.xyz/Article/details/gtzdzpqmau.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtvaeqpytd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtrfoggclc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gtfvumelhw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gtaxrfkhox.html

[E06] 替换子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksklnhir.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtsjctdefs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhoulong.xyz/Article/details/gtmubweiwz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtjrbfekhm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtqybfrupb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtiyaqksrp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtsukejlbv.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtazbmhhia.html

C#:   s.Replace("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtwvgjyggd.html

[E07] 按分隔符拆分
来源：http://dali.ppjwa.cn/Article/details/gtlwocihhw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.meibo888.top/Article/details/gtumzczfxz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytckdoms.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gtpxtmmgof.html

TS:   s.split(",")
来源：http://dali.tian-w.cn/Article/details/gthkenqghv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtnedbmjmv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sxryk.cn/Article/details/gtecnaffcs.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gthnmsqeaq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shuidangran.top/Article/details/gtnwmuzbgg.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gtnylngrbz.html

Py:   ",".join(items)
来源：http://dali.zhixingplan.top/Article/details/gtuqozdgsf.html

PHP:  implode(",", $items);
来源：http://dali.andypj.xyz/Article/details/gtpxvivnei.html

JS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtcyzulvhj.html

TS:   items.join(",")
来源：http://dali.cucudq.cn/Article/details/gtstrsxyrx.html

Java: String.join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtfofhkegp.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigufen.top/Article/details/gtvaqubcqt.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtfdrjzbzt.html

C#:   string.Join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gtxyxsaltr.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gttihnfsoo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinqigufen.top/Article/details/gtkxsfjphu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xinyue.icu/Article/details/gtihtzcpdt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.haohaochexian.top/Article/details/gtdbzqwiss.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gtzotnzobu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gthuixjbrv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.tianlin.xyz/Article/details/gtulrowdky.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtwfnvlrik.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gtdnpdzkhj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtfsajvuuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtjxjfgbsp.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jlsjyb.cn/Article/details/gtuenwwvkw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtmkhliobm.html

TS:   "7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtlbcrpdnq.html

Java: String.format("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtiuztbgzr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtrgjrstef.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtreeqnxzy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsgszegi.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtqbxguvny.html

Py:   s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gthtlkpgzg.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtuwyzgzvx.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtmwiwjorm.html

TS:   [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtpsnagcll.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ppjwa.cn/Article/details/gtqviqbprd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtcgpbrloz.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtaknfmgsy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtsvjbxcwk.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzysnqft.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtepotihqc.html


<!-- 参考信息 -->