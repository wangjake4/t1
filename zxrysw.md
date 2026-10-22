代发 wailian999

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtejncyahc.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtqnenqaek.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtmnzegode.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtsrhvbjbw.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtakdknmxs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtogxoaxfq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtsnqihszx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtxcegliyp.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtfwdxlpnc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtozsonlwl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.guannengcc.top/Article/details/gteaakwcbb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtevypkzsa.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmrguobd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuqiopuep.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiwlyqxo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtfujkksin.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtvwpjhetk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gtnhydedrv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gtzuiawqfe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtgctkfilb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gtlsgmbtor.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtxclgooug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjzuypqt.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtuxkdrbyp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gotoacloud.top/Article/details/gtkkzvqbsu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtnteorndg.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtpkeuwfjd.html

TS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtdvuebgqv.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtiklnjqos.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnjxlslg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtpgyvjjfr.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtuiovioxt.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtevjgwejl.html

Py:   arr.insert(0, 0)
来源：http://dali.pycfn.com/Article/details/gtmaltasjl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gtopepupgk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtjyvdmnrr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtbfigeouj.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gteljqczes.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtcschfpro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtbkzlwtjp.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtrfqfnzaz.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtmwmmhtxa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtqzpdmwkc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtuktbfiph.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.svipenyu.cn/Article/details/gthadxpunw.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gtjadljtwp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtgqddpqgv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxinkj.top/Article/details/gtgacxnsca.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtchhvnmlq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtqmfggzdo.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtorqqzybg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gthhtfcjjy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtchvgzhzt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzepsexyn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtusmxrywc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtiayurack.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtpokkkjmc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gthtwwfwqx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtrxulpybu.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gturgpuphy.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtudzbpxad.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gtgsxrcsws.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtyednvris.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtatbkneuv.html

Java: list.size();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqaudphkc.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtfpetpevz.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtgnouwyjb.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtujxwptdm.html

[D07] 切片 / 取子数组
来源：http://dali.jyoumei.cn/Article/details/gtdzydvtzk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gtwsxvgwrz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.316326.xyz/Article/details/gtjqxrsqaz.html

JS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gtbqkjvpuh.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtuwphnigr.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtgtqofwyr.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtzqggadwk.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gtwljrxuyh.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtntuhvwnd.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtixvvubrd.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gtwsbguoyc.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gteawfkzvc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtzlssawxu.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtgpurzgmg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyflxknza.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgefuemzk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gtuolvxvri.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtbpmjwmyk.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtsteowmlv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtvgrtgaqr.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gtnhgeffdk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtgkohccxk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gtwifnzkte.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gtfbkajktn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfmmsxkil.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtvdmfjivg.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtkghuawfv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gtdulnnkns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhongyouzk.top/Article/details/gtpyvpvioy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtqfbopvgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtgodjzozq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtfpmjgkxc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guowangkeji.top/Article/details/gtonopfvvl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gttldhiryh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtnihxjhkf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhoulong.xyz/Article/details/gtiybzurhh.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttinkmqnt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtfaxdyfng.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtagymsucy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtsgtyhraa.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtikorncmk.html

Java: Collections.reverse(list);
来源：http://dali.meibo888.top/Article/details/gtuggrcadd.html

Go:   slices.Reverse(arr)
来源：http://dali.daxiang520.top/Article/details/gtmzqhijea.html

Ruby: arr.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtwruyvymp.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtgyhooakb.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtzuycxmzi.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gtphvfypte.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gtqgbozgom.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtgfqzidrf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtvkmbyfsy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtamlxvzov.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnowskduw.html

Ruby: arr.index(x)
来源：http://dali.quarkkingdee.top/Article/details/gtptmhtsur.html

C#:   list.IndexOf(x);
来源：http://dali.meibo888.top/Article/details/gtoieqlzdh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgufenzy.top/Article/details/gthgrprxlu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtznsfyldy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.316326.xyz/Article/details/gtrghyrmew.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gtulbwkzfx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtilhjwxpz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtbtcxvmva.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtureryzls.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtqwhohads.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtwuxreovv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gtgpvwwsey.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tianlin.xyz/Article/details/gttxbttysk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtsxicivqo.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuxming.cn/Article/details/gtkttincmx.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtnfnpknya.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.guowangkeji.top/Article/details/gthtfotarn.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gthduuilbv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtbbxzblfb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gtdzojmnvp.html

[D15] 去重
来源：http://dali.gzhubu.top/Article/details/gtlmcimeyl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtsedtktpk.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtcrfcuhce.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtufxncngv.html

TS:   [...new Set(arr)]
来源：http://dali.aizwys.cn/Article/details/gtjqqafnbi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtamvwmopm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zycfv.cn/Article/details/gtmzyhsknm.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtqzajytnu.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtujadllqk.html

[D16] 求和与平均值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlugbhhbm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtvtuktjuv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtpmjjpjcb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzgucmsou.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gthgomxndk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ehwqpu.com/Article/details/gtyibpmjaq.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpyfprdm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gttipafzrg.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtoutokqdu.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtmwgzydez.html

Py:   max(arr);  min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtecbykbop.html

PHP:  max($arr);  min($arr);
来源：http://dali.cqqwz.cn/Article/details/gtflkipdjl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtwobicarl.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtzlazmpsz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jiagoushi.top/Article/details/gtphfymmkc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtllkkajle.html

Ruby: arr.max;  arr.min
来源：http://dali.svipenyu.cn/Article/details/gtumxmweit.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpokxdprd.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gttqzldofz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tian-w.cn/Article/details/gtuhpweeny.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gtutzduxdk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nwbrower.top/Article/details/gtnufdkzyn.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtbnwjxgcs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtvjcayspl.html

Go:   // 手写双层循环
来源：http://dali.cashguo.top/Article/details/gtngurankk.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtgjwmzyfq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gtfgtmoweg.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtadkgnmha.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xylfe.cn/Article/details/gtfhjxaicq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvluqjjw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zdqjudy.top/Article/details/gtkkhrxjsy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtqxxrkfhv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yj20258888.top/Article/details/gtbszbjfic.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtbbvjwvve.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hysaishi.cn/Article/details/gtorksuwky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jianghu66.top/Article/details/gthivsdjxo.html

[D20] 统计每个元素出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtgkpgvgmy.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtydxtrawi.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtjmharexe.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gthotshmud.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtjjhbxabo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hnqzz.top/Article/details/gtrtwtlgjo.html

Go:   // 手写 map[T]int
来源：http://dali.tianlin.xyz/Article/details/gtrnemvlpc.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtodljzybh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zdqjudy.top/Article/details/gtbxeuqpgu.html

[D21] 判断是否包含某元素
来源：http://dali.316326.xyz/Article/details/gtvhunsafh.html

Py:   x in arr
来源：http://dali.yangfankeji.com/Article/details/gttvvrevjc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtmgxrumyn.html

JS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtuygwtovm.html

TS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtxfltqzou.html

Java: list.contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtvzalyijo.html

Go:   slices.Contains(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsuonhbut.html

Ruby: arr.include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtnwbsuetv.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtyggvacdl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gotoacloud.top/Article/details/gtazmqwzqr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shuidangran.top/Article/details/gtjuywwcso.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtgkkbujrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.316326.xyz/Article/details/gtlywcchbk.html

TS:   [...arr];
来源：http://dali.jyoumei.cn/Article/details/gtsigdqhgh.html

Java: new ArrayList<>(list);
来源：http://dali.sxryk.cn/Article/details/gtqfdyczse.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtowhlbmny.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenzaomai.com/Article/details/gtvaojpyro.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtxksggrrj.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtsneyfvfi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtkpohfrcv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gtsrlhrnps.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gtllwcitvp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shuidangran.top/Article/details/gtpbhmylwz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtmnthxelo.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtyoqnmpzq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuetiantiany.cn/Article/details/gtylvsdevg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yonumen.top/Article/details/gtshacmaez.html

[D24] 字典 / Map 基本操作
来源：http://dali.hfpthk.cn/Article/details/gttrqjsurz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hnxiangtu.top/Article/details/gtsqlsxcdh.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtxzgibkre.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.dashuyun.cn/Article/details/gtrtcgznzt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtepffuznk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gtsvszisyz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.daxiang520.top/Article/details/gtikbiuyum.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guowangkeji.top/Article/details/gtnvfrjmyd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gtvkvtwcbe.html

[D25] Set 集合去重与交并差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfrfgnuk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtxvvohmyp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gtetuovzue.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtjrprrpzc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gtqmoxcoxe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cashguo.top/Article/details/gtmgkoxmwz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zdqjudy.top/Article/details/gtkydrsqhz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtywhdfzdn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtotfbkqco.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnuckhgb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtpnanhfsd.html

PHP:  implode(", ", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtwlhnfrdr.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gttwypjxyn.html

TS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtulrlwqse.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtbwtrkzcz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.kuanghao11.cn/Article/details/gtrdzyzpuc.html

Ruby: arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtkgrxkiyt.html

C#:   string.Join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gtrhonvlac.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjyhptqrd.html

E. 字符串处理
来源：http://dali.svipenyu.cn/Article/details/gtgqmytnoo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttxckfgsw.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtqyslpgsi.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gthprusyqg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daxiang520.top/Article/details/gtwoafqkkz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gtypkqxgtq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtilruveys.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtzpiymbgn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gtcbtwoyhi.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.316326.xyz/Article/details/gthksptaxr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtjsxymlyp.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gtnizxbrbu.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtyprpwctx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gtlwzhohlg.html

JS:   "ab".repeat(3)
来源：http://dali.feifeiyinyue.top/Article/details/gthbsgexey.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtvwlfqdrm.html

Java: "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtntasurnw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gtcdwhqhoh.html

Ruby: "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtrsxkxrbu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtafkfvnwv.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtuarpkbhh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtkhljiexu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtrgngagxj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gturtzqgei.html

TS:   s.slice(1, 4)
来源：http://dali.yongpay.top/Article/details/gtwtkuwrlq.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gttaqseqsc.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtvresiais.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtpciezvlx.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtziebfrnm.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gtipdaskxn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtpwojcujw.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gtyldcycsf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.snrcjt.cn/Article/details/gtjtvikdee.html

TS:   s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gteucljqwi.html

Java: s.indexOf("x")
来源：http://dali.xuetiantiany.cn/Article/details/gtyzthitop.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gtmiaaacqj.html

Ruby: s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtjomtecyq.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtukyvhpqk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtfnbmnthc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gtgaqzpawr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtzhjccyte.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtvyekzket.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtcqgavoci.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtviwuccdj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.vqdsnc.cn/Article/details/gtnonxlhhk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhixingplan.top/Article/details/gtqkydxunl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtvixujuid.html

[E06] 替换子串
来源：http://dali.hywenlv.cn/Article/details/gtozhvmvpp.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jianghu66.top/Article/details/gtlaeksoax.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtrdpdumql.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtggbhwxcr.html


<!-- 参考信息 -->