代发 wailian999

Ruby: a, b = pair
来源：http://dali.tian-w.cn/Article/details/gtchtubptv.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtzdoxhstd.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtvupxemiy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtfiorgfva.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gttvcrkyss.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtledgpfgh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrzedjqd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfhhqofke.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtqfumrvsw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtrmmnjmnq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtognctyui.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjvdivfxs.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtbcbrprnn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtydgczrpk.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhoisuvr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gthjaymfmh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gtiopeojeh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtmwrukmjm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtmardsmya.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gtfylccwvz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtizjwseua.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtuabnkjzr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gttfxwvajk.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtnwbxqsfi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gtebolcykf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtiiybfpdu.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzigobokm.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtqzbvwroc.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtqsxsnphd.html

Go:   arr = append(arr, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtcottxstn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtfffjtagj.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtqkprxukc.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gtqqlqeqnw.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtjhvhbyzw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gthxfpxwqp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtrltckxjw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtmiqjsxxj.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtdufxkkmr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtokxrsprd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tianlin.xyz/Article/details/gtbkdqgrzj.html

C#:   list.Insert(0, 0);
来源：http://dali.sysykeji.top/Article/details/gtimzfetjn.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtxmdyumld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtcfwbrtjk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtagcfbnor.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gtftwijutf.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtkybdcplh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtchjsxhme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfxfhnzs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.havefunace.top/Article/details/gtjfgkzimu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtqlyxuozp.html

[D05] 访问与修改元素
来源：http://dali.wangshuangyany.cn/Article/details/gtpvfhjhfp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtpgxllgbr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtbldvoiyz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtfausqmlp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtghbgfzoz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtvzzcbxyk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtbytzkvsl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtviuxvrzh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtwruanbju.html

[D06] 数组长度
来源：http://dali.ivvv.top/Article/details/gtaxryyiuy.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbscmykst.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtjbnkiesz.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtsiihytkk.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtgtytrhbw.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnuvphfn.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtisunsvpi.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtarrbxzzm.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtirepdadu.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtqepglzhe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtxikcodkc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaxsmfak.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjpptfsju.html

TS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtbuxtlrnb.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtmlljadwh.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtqyauxirl.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtjlznqwfu.html

C#:   list.GetRange(1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknbaeljq.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwjjzemv.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtzgchsjym.html

PHP:  array_merge($a, $b);
来源：http://dali.gzhubu.top/Article/details/gtctsrxsqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gtjlodiail.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtzdhmqk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtzsjsvxqv.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtydsniqkj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtdchsjktb.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigqxxbxe.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtarphkntd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtthfgjori.html

PHP:  sort($arr);
来源：http://dali.chenlongwang.top/Article/details/gtknzqzejw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gttutingot.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dianchejie.cn/Article/details/gtocxplxmv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gtttfuyaty.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtnhpbdxuy.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gttodvxvvi.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtqbejjakx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpahjyfdt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtvwavjjsn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtevlxsqvs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtcopiaddb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtlxjcsvxc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxuanxn.top/Article/details/gtcstqdnmx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shangyingyoupin.top/Article/details/gtaogblhnt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.daxiang520.top/Article/details/gtesjpsrmr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yongpay.top/Article/details/gtnvxzuics.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtbogpkvtq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxenqmts.html

PHP:  array_reverse($arr);
来源：http://dali.zdqjudy.top/Article/details/gtjjjplvrt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtqyitxgjf.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtrltaowbj.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtczqydhle.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gtepwbpnek.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtkjriffgl.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtxjilbiyr.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtanlhnoyz.html

Py:   arr.index(x);  x in arr
来源：http://dali.0kj1m.cn/Article/details/gtlnlnayyd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtukavpwon.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gtyitrfbmp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtajyharar.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhiwuduotai.top/Article/details/gtfkgtjpdx.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtasiblkdb.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvejeilwu.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtpevscuuj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gthsevomyq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtrjctwljy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmsggijaz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtjlqzhuvt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwovqhfe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtjjsobivq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gteumcfsuh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtpsmnuvxl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.havefunace.top/Article/details/gtlsnhnhaw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtknjfmhld.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gtsbkifkfa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtbonetkpv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gttjzqoqez.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtgyirpkcr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hammf.cn/Article/details/gtgucgglzn.html

Go:   // 手写循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriiqmknz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtdlzmoprt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtheznvgks.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdymnzki.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndiuqalw.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjnwlyou.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtaeqbaoia.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtloqpatqf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtxdvrjcrx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtynyoulgx.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtdlkvybye.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbkaztmu.html

[D16] 求和与平均值
来源：http://dali.ivvv.top/Article/details/gtnflgxaus.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.havefunace.top/Article/details/gtxyrzfsmo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtlzkqfmeb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gttillzqci.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gtpgdteuzx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.bjfxy.top/Article/details/gtisjlrcyl.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtcnexyqrp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gotoacloud.top/Article/details/gtxikoeyxx.html

C#:   list.Sum();  list.Average()
来源：http://dali.hywenlv.cn/Article/details/gtbggwxoaf.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gtwyvyydnz.html

Py:   max(arr);  min(arr)
来源：http://dali.cheryme.top/Article/details/gtiiwsbpsw.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gticfmnaze.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gtnsasnbdw.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gtpbsbjxxn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtsxvkaiza.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtoqhnxbpn.html

Ruby: arr.max;  arr.min
来源：http://dali.fengsongda.top/Article/details/gtzbyywpnb.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwebtequ.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtpyaazvwi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yuxming.cn/Article/details/gtdfdrtzse.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gtmjnzufsa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jqgufenzy.top/Article/details/gteouyirwp.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gtwltvyhme.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sufxvd.cn/Article/details/gtadzncwds.html

Go:   // 手写双层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtxvvssrcq.html

Ruby: nested.flatten
来源：http://dali.chenlongwang.top/Article/details/gtbtxqtwur.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtqizoctul.html

[D19] 按字段分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfuebfvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtjrltensr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gtzygcbprh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.0kj1m.cn/Article/details/gtaxaovpxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cashguo.top/Article/details/gtrqriulvv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hfpthk.cn/Article/details/gthltefrns.html

Go:   // 手写 map[string][]T
来源：http://dali.xuanzx.com/Article/details/gtnirzotix.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fengsongda.top/Article/details/gtryqbgpeh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gtbjqdacxh.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtargptzvb.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtninuovmv.html

PHP:  array_count_values($arr);
来源：http://dali.daxiang520.top/Article/details/gtrdvahmtq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtmbzwopnt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtymqjkyqv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtesswouqj.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtvdrfwvar.html

Ruby: arr.tally
来源：http://dali.quarkkingdee.top/Article/details/gtpkvmoskf.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gogol.net.cn/Article/details/gtjioivvap.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjcnjvce.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtghcpvogj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cdnleiting.top/Article/details/gtgltqkxyt.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtnwtssztf.html

TS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtzlittyoy.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtjllyoxdx.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtqjffgnig.html

Ruby: arr.include?(x)
来源：http://dali.cheryme.top/Article/details/gtrjoniqqr.html

C#:   list.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtpxoruusz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gtrowfnuuq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbpvfnivp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jyoumei.cn/Article/details/gtawumemre.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqmwaxacn.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtzibnamvt.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtgsciflzv.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cdnleiting.top/Article/details/gtxwaouixa.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtnnmabeya.html

C#:   new List<int>(list);
来源：http://dali.ivvv.top/Article/details/gtiuqohfvp.html

[D23] reduce 累积计算
来源：http://dali.yvedp.cn/Article/details/gtstpwzubi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gthaqzzfma.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhixingplan.top/Article/details/gtdxkfojpy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtedoagkws.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtvabbtttp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigfzy.top/Article/details/gtcoukpnae.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtmyvqigev.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtyzcgsabo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ehwqpu.com/Article/details/gtlbccbfbp.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcxjdgfql.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gtoogwukqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhongyouzk.top/Article/details/gtdscxhxfh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtenwhntnb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gthkgvarpp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtshdjllqn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.chenlongwang.top/Article/details/gtsfmyyrvq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtuxpkuixv.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yvedp.cn/Article/details/gtgjgaxqtj.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtgcqohcef.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gtshiyszso.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtuhpbuhqc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gttstorcur.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gtrqxzcsup.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.pycfn.com/Article/details/gtaknmantp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.mhx1999.top/Article/details/gttkzlzwye.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhixingplan.top/Article/details/gtiahapksi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hammf.cn/Article/details/gtsyxupprl.html

[D26] 数组转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfqskyrs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sweek.top/Article/details/gtzpmllvgy.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtaanuaydp.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gthyzpvobw.html

TS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtovssnlgj.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtiycnlbmp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtwfhjrcpb.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtamtivfri.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gtiixugkwa.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtagkddjie.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtmtnmlvtl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtycrfutuf.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtkcvukflx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.mhx1999.top/Article/details/gtzsfjbsaq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jianghu66.top/Article/details/gtxpqvejzl.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtbsdyvxrh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.tianlin.xyz/Article/details/gtopmlqyea.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtineoybex.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.fengsongda.top/Article/details/gtjqsifuyt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hywenlv.cn/Article/details/gtfbeoxcvi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtsmthvxvx.html

[E02] 重复字符串
来源：http://dali.dianchejie.cn/Article/details/gtagcxosow.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtaffwwuyq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tian-w.cn/Article/details/gthcmpmbtz.html

JS:   "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtvhxsylyz.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtnahfbcea.html

Java: "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gtprszexgq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cqqwz.cn/Article/details/gtajbwlkhl.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtmxjnyfdj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtfdwxldfp.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtpdsbhbos.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.guannengcc.top/Article/details/gtfmeenhtb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtyjqxbwpk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtsatazkuk.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gttomeindq.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtimxkstnj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtmsycrfxj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtostzwxpr.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmascplu.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gtkpmvjcga.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gtznwtbahz.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gtulzmokbo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yangfankeji.com/Article/details/gtzfnyttfk.html

TS:   s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gtxwhwmnqg.html

Java: s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtictyurja.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtfkkuuzwi.html

Ruby: s.index("x")
来源：http://dali.hnqzz.top/Article/details/gtlmypmlqa.html

C#:   s.IndexOf("x")
来源：http://dali.pycfn.com/Article/details/gtonbwqsky.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.feifeiyinyue.top/Article/details/gtjygxiobw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gttdtxitgm.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtbqykrkyd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtaeyswcys.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jyoumei.cn/Article/details/gtuuhjnvsd.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtsvcikejm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xylfe.cn/Article/details/gtptrinftw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtbbngbijk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.birdmap.top/Article/details/gtegjqfspp.html

[E06] 替换子串
来源：http://dali.fengsongda.top/Article/details/gtyhtlzhbb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtvfgklrfs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtuxquqonv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtnggeynqv.html


<!-- 参考信息 -->