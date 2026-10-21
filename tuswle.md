代发 wailian999

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtjzhsnqpm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtwpnlpyfw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtlevjkqtj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnxovtmed.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjeafndlz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttbmsoyqj.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtnhexcciv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gtgnjhwprh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtzjfqalwn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtwuvcuzpq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtblferqqu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gthzmtmsmx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gttryfpodq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtqcjwzobg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtiyqrrt.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtjlkpckas.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gthnchwoej.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtezumvubt.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtlllzzqyg.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtadaqxhyu.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gtpezdjgbu.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtxmsqzcav.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtxlrhcmvx.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gtlfmekfbi.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtxwbvwita.html

Py:   arr.insert(0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtpcsciaie.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtoaaxxzen.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtwiykrigh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtlukkvdex.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtsvktpnjm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtvkrdtqbq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xylfe.cn/Article/details/gtojhrlfnu.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtietxxboc.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvpsskfm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gteztdfejj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtoylayjby.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhiwuduotai.top/Article/details/gtdaecixpq.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtzabgqhiu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtxulzarfj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqfjcyfk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtgyzuegdz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jlsjyb.cn/Article/details/gttewnkzzd.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gtibkolqqi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtauooebck.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtrpbhvetl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtecscmwqs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtxaenrkxf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtuovyibfa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtferbnwju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtxtvrnywb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gthlhtpcxj.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtixglizup.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvdninbw.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtqqgsehhf.html

JS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtpjzwibrg.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtymwamsog.html

Java: list.size();
来源：http://dali.jinqigufen.top/Article/details/gtrssilysx.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtbhpixxgs.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtkcoptnzp.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gtozzbcwwc.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtusdhovcz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtkmbjwguv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtwocauefx.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtcmvllxwh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtposblbdo.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtqfewfjrr.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gthamsurxj.html

Ruby: arr[1, 3]
来源：http://dali.316326.xyz/Article/details/gtxquiwkmj.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtdoykkjch.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gtmclwgoky.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtfenpfybs.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtkfnmijht.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtgegotceq.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtvwwxzsxj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cqqwz.cn/Article/details/gtbyzppfnr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gtefojgmcs.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cdnleiting.top/Article/details/gtbjyyxpnw.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gtiktmvqlv.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtbnfxevkn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtykcyvurv.html

PHP:  sort($arr);
来源：http://dali.xziqi.cn/Article/details/gtqvttlpcf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtxkptyvth.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtzhfmndnx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxinkj.top/Article/details/gtdxnscfbt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkavnsqab.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gtudtvgcag.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gteefttmlt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtliooemgx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtqhnidaoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtgwemulro.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtabkcznpa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtlnkrpbwi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtkmqoroae.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gtvmgdsfep.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtgfbehknk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtwuzkprid.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtvlaieoxo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxuanxn.top/Article/details/gtnhrktcrn.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtbpubnopk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtgbapsjhk.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gtbjzkkwom.html

Java: Collections.reverse(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtjfjgrcff.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtzbrpxuvb.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gtwkwrtyfy.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gtxyrjchgd.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjlbjkab.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtxkclrwjo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtkffwxdiz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gtuuezvkrr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtsyuikbod.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtmxlfhkmh.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtfgeqvekb.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtkyfsvemp.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtbofyvxxv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangdashe.top/Article/details/gtbugvzvue.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gzhubu.top/Article/details/gtwamxddih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gthfytjldh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtswtkpqme.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtshpbpnlz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cdnleiting.top/Article/details/gtdauaeyzc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hywenlv.cn/Article/details/gtlvpjqbpb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gtlfphsvqs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtunrmrfys.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtjqknoupq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtsspqhseu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gteaiemdcs.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtpwsfptoe.html

TS:   arr.map(x => x * 2)
来源：http://dali.havefunace.top/Article/details/gtkqktdecb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpsfblta.html

Go:   // 手写循环
来源：http://dali.guannengcc.top/Article/details/gtxoxcpnbu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtksxkxdxa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtrxtcmieb.html

[D15] 去重
来源：http://dali.ydzc1.top/Article/details/gtvvqfsfsd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtkxpxvuaf.html

PHP:  array_unique($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtikttavoh.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrqmuxiq.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtachlverp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sysykeji.top/Article/details/gtnjewiiek.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gtmjqubcnp.html

Ruby: arr.uniq
来源：http://dali.hywenlv.cn/Article/details/gtkbkzudtb.html

C#:   list.Distinct().ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyitycsg.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtwrgsiqww.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtyppepdqt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtwxwasbsc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtneirpeig.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtwyqtlmyj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hammf.cn/Article/details/gtabhciiqi.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtmnccptpy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtyaoujhez.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtcjzrmgdh.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtyswvhjto.html

Py:   max(arr);  min(arr)
来源：http://dali.ydzc1.top/Article/details/gtzulpdhdg.html

PHP:  max($arr);  min($arr);
来源：http://dali.svipenyu.cn/Article/details/gtimfmrsnz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gotoacloud.top/Article/details/gtendkhvoy.html

TS:   Math.max(...arr);
来源：http://dali.xylfe.cn/Article/details/gtikejjqnj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtesiswgec.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fengsongda.top/Article/details/gtrmchrfma.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtdjeilqsr.html

C#:   list.Max();  list.Min()
来源：http://dali.hnqzz.top/Article/details/gtraimgaxs.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gtlhfppiek.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sysykeji.top/Article/details/gtekzmcxnf.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gthekgyhax.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gtnxybvixz.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gtroxfhunk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhixingplan.top/Article/details/gtqhiuqnyl.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvvbafpiw.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gteomgnifq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtjkarccqk.html

[D19] 按字段分组
来源：http://dali.gotoacloud.top/Article/details/gtwfbdacom.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daxiang520.top/Article/details/gtltvycnwi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtaiqfxuzb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gtjnmlhkmk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtiiyzyjzl.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtjpiowayj.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtkoemhafy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtgtbxddsk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtqedgyqxl.html

[D20] 统计每个元素出现次数
来源：http://dali.meibo888.top/Article/details/gtjphokewd.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtkbsmczzj.html

PHP:  array_count_values($arr);
来源：http://dali.snrcjt.cn/Article/details/gtohhlffmu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.svipenyu.cn/Article/details/gtnhxsdcav.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtyysuenpa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ydzc1.top/Article/details/gtutwscwfy.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gtxnwdmoac.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gtsepcchuy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.fzhhl.top/Article/details/gtdxwftybg.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtesabdetm.html

Py:   x in arr
来源：http://dali.cqqwz.cn/Article/details/gtebqwflvr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jyoumei.cn/Article/details/gtoxyykeba.html

JS:   arr.includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjpwtnakk.html

TS:   arr.includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtndzbvasp.html

Java: list.contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbpsggtt.html

Go:   slices.Contains(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtidhduyag.html

Ruby: arr.include?(x)
来源：http://dali.aizwys.cn/Article/details/gtodctwfse.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtannewsro.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pengpengdd.cyou/Article/details/gtnyxyjxin.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.daxiang520.top/Article/details/gtbncxpiev.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cqqwz.cn/Article/details/gtsmhctvij.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttzmthaum.html

TS:   [...arr];
来源：http://dali.yuanzhike.top/Article/details/gtqnorsniv.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtjdconzrj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysopwykh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.sufxvd.cn/Article/details/gttzzqzadc.html

C#:   new List<int>(list);
来源：http://dali.iojbl.cn/Article/details/gtolcbelzm.html

[D23] reduce 累积计算
来源：http://dali.tianlin.xyz/Article/details/gtvtvpimzw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sxryk.cn/Article/details/gtwtosbudz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtptfgccxs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnuurpgha.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fzhhl.top/Article/details/gtzdgylqem.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtnjtpaiov.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtcwhlhesu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.cdnleiting.top/Article/details/gtqtdtdbxi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtckuymfnh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gtylkdcgnq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhixingplan.top/Article/details/gtlhpfhsje.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtktrqzndb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtvzamxuey.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtuwbndmww.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtulmwiidj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnqzz.top/Article/details/gtudtnzkxf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtshfcgdwm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gthkfyybdc.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtydxwxiwz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtllnqggea.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuanzhike.top/Article/details/gtlzcxbixl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmberdczt.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtmtjmsqbw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtrkjgdfwt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtdktzwdjo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtclzgfall.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtdehdomfj.html

[D26] 数组转字符串
来源：http://dali.smart0.xyz/Article/details/gtizeocdkf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtirkrjmlf.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtevoxwsqm.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtnogsfyld.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtjpvjcltw.html

Java: String.join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gtbfbeddbx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gtcdgdebkr.html

Ruby: arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtqstmfblk.html

C#:   string.Join(", ", list)
来源：http://dali.ybcxt.top/Article/details/gtphygwmhj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfruiljpj.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtmvjvqzep.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqvecoefm.html

[E01] 拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtbjtififw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtvtnraais.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtyzwaklss.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.snrcjt.cn/Article/details/gtcbexmvxs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtchjgqolv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtefszykkr.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgufenzy.top/Article/details/gtvxgmprvd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjutqaha.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtkoarvcfn.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtrkbllasg.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtdhqlrgpi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtdhbdwysb.html

JS:   "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtdwonipwr.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtfaiuebcx.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtkgrvhdej.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gtyhmpbyhv.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtnlcdjpxz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtbqtuvqsm.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtlbzpsawk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtcittfnip.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtvzmmhklh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtodmxfygy.html

TS:   s.slice(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gteikrxudl.html

Java: s.substring(1, 4)
来源：http://dali.zhengqikj.top/Article/details/gtyvpxkouc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.gaohongyu789.top/Article/details/gtipzdbmrj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtyenmytal.html

C#:   s.Substring(1, 3)
来源：http://dali.c1oappe.top/Article/details/gtpnmjwphn.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gtbniwopld.html

Py:   s.find("x");  s.index("x")
来源：http://dali.andypj.xyz/Article/details/gtkzkaugmt.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtkmvcgesq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.cdnleiting.top/Article/details/gtikhtoyxo.html

TS:   s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtuoqqeigv.html

Java: s.indexOf("x")
来源：http://dali.cdnleiting.top/Article/details/gtfkpjxsvs.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtnyrbqhdy.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtqwqaajcl.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtlrocafqf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtlowpmooh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtdzmcbogw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jianghu66.top/Article/details/gtokczqvgw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtvpddiutf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jlsjyb.cn/Article/details/gtaxrywoct.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zycfv.cn/Article/details/gtfanmdfte.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtztenwkng.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.redwolf501.top/Article/details/gtnpcyqofa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtpsckfqie.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtlicrbiur.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtvvtzosbw.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xziqi.cn/Article/details/gtqcxnrdnu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtxlmhywwc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtecuwngrv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtxnbhppqa.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirrnfbwm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtelbqzabm.html

C#:   s.Replace("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtsasqfybs.html

[E07] 按分隔符拆分
来源：http://dali.xylfe.cn/Article/details/gtwtcgtqnh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shangyingyoupin.top/Article/details/gtohjkjmyv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtixcbgyyq.html


<!-- 参考信息 -->