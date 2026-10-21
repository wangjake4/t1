代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaxqxtphx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtgqskezgg.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtznbinhbm.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtctinzpoe.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtisgrurpa.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtnztegnxz.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtyzolbkkj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtirmblkgo.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtedyefwzs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtdrdbuxzl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtxtxpbcaw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtqmrjrnvs.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtyucprctv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtaaopwpkv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtrorqzezg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamywggfc.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gtpsivsxhl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmzdxopts.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtbetmxbnb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtjakrzjxi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtcbarphgt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtumnwwkib.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtgnqacbbo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gtekvhjomn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtecmzeddq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsprieoqo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtdkxmreiq.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtglbfjvxd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtpqfompbf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtikjvvkyf.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtfedakswz.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtgnzccebb.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gthkkdietp.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtyntbgiki.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmqchutm.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtbtyvoehr.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtethifznf.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtxpibkfou.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtoqyjljcc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gtzflhjrfi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotoiamnp.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtcmyuvazy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtlnirdvoy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gtqyzqmhon.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtsfzfujao.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtynjhpdib.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnsngser.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gtxfpiinbm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtgubptwcy.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtnugxkeyg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtciyhqqxc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtqbcemxid.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gtmsduyrlk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtukyzqphy.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gtzreegxrc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtijvzglhs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtkzomrvps.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtguiuyssv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gthjoyplnp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gtttisswpo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtpluvgtba.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtnaolkdle.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtuszmujuy.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtmajuolvb.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtkfsoxvjj.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtcumzhsdm.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtrjxaeasa.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtqioghpoq.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtmtmyqsxf.html

Go:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtwxgalnmz.html

Ruby: arr.length; arr.size
来源：http://dali.yvedp.cn/Article/details/gtbaquelig.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtxghkfauo.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gtqnzhhvrz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gtbmrmbirv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtdyohkulg.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gtakbvpzwx.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtdslzbiau.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtfhngftyh.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtdsjxupxf.html

Ruby: arr[1, 3]
来源：http://dali.daria6918.cn/Article/details/gtmggowihs.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gthqtolyev.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gthkzhrdnu.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gthadnarsr.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtesphhety.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtuyuoreyd.html

TS:   [...a, ...b];
来源：http://dali.gaohongyu789.top/Article/details/gtbkkqluwx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobixkqru.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gtltaogivi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gtjmllvhus.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxvfojhxq.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtldmjwhzh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtkqpkzrzx.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtzzyezsej.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gtdklchfsr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gtyqelviuq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtoaqtoaqr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtnomyaesp.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtwttjgkps.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtixogcdab.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gtkpsigxkg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gthnmfdrkk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gthmtbhbzt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtufpjxtvu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtxjlzfaog.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumicjpo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcfuwlcn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gtnmnuihms.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtayylgvvu.html

[D11] 反转数组
来源：http://dali.sxryk.cn/Article/details/gtcflitekt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gtgwqpensc.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtvaxnwneh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtparmrrie.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtscszstvn.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtoviwatup.html

Go:   slices.Reverse(arr)
来源：http://dali.jianghu66.top/Article/details/gtueedqdhb.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtydjcvbjp.html

C#:   list.Reverse();
来源：http://dali.haohaochexian.top/Article/details/gtpnzfdnpg.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtipznxlza.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigufen.top/Article/details/gtxvijdhkc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybhjktlo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtuezvxook.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadzngzpg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxinkj.top/Article/details/gtmaldwcja.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtcumlfucp.html

Ruby: arr.index(x)
来源：http://dali.yonumen.top/Article/details/gtwwkltyti.html

C#:   list.IndexOf(x);
来源：http://dali.birdmap.top/Article/details/gtjyghdihp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtialhfdpj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdultoip.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hammf.cn/Article/details/gtawhmikdu.html

JS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gtwcmoxxaq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shuidangran.top/Article/details/gtimcnvafp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtdvwnhnmw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtjgjwhzmq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gttrelvzfv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtsammccfk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.iojbl.cn/Article/details/gtdscsanvb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtxtyxnhsx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtrkaqgndi.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtmylhnaeh.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtynhfptar.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtbxwvbpdh.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtzamgyuwz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtemdroatr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtzlwfciuk.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtmlevsqac.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtfyctflnz.html

PHP:  array_unique($arr);
来源：http://dali.jinqigufen.top/Article/details/gtlpnqceyp.html

JS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtkgzfercn.html

TS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtthouivyu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtpcfvsfwp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvsvykjl.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtthbzjsuc.html

C#:   list.Distinct().ToList()
来源：http://dali.tian-w.cn/Article/details/gtzgkvetco.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtlvomwerj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtkmyvtzzc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtawmqqxwe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtassigvji.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtfwucvgiy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.snrcjt.cn/Article/details/gtuudsgcgt.html

Go:   // 手写循环累加
来源：http://dali.ivvv.top/Article/details/gtxetwgank.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gtluyaxnii.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gtynzqvwpv.html

[D17] 最大值与最小值
来源：http://dali.hywenlv.cn/Article/details/gtwlxgmgym.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtzbqcfgwl.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gtuhxhnwwt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuanzhike.top/Article/details/gtimxtubzk.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gtixfiuavy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtzoczmpdc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtgibrfbtl.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkufxkakr.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gttiecdzhh.html

[D18] 扁平化嵌套数组
来源：http://dali.sysykeji.top/Article/details/gtggygfcqb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfocibjc.html

PHP:  array_merge(...$nested);
来源：http://dali.yongpay.top/Article/details/gtzylyhzxb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gtgqpkwrur.html

TS:   nested.flat();
来源：http://dali.jyoumei.cn/Article/details/gthwgqttdp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtmivhfrhe.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtssabbkoi.html

Ruby: nested.flatten
来源：http://dali.chenzaomai.com/Article/details/gtoqojvjug.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtgehkomjw.html

[D19] 按字段分组
来源：http://dali.iojbl.cn/Article/details/gtivtqofvi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuanzhike.top/Article/details/gtpxftvomc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtkrdwfatj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gtsjauyzmf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtdhppngme.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtnvyacckp.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtufpgvgjd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenzaomai.com/Article/details/gtvgpfvksb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj202588.top/Article/details/gtaccjgrqq.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtbmybigpo.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gtvqrmkpwj.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtxgjqgbbl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtbhlnxjmm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gtgvcrqyaa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gttwtbycyo.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtgylgqttf.html

Ruby: arr.tally
来源：http://dali.yanxiufei.cn/Article/details/gtxwrnwiwk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.kuanghao11.cn/Article/details/gttzdbpdbe.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gtuzxihnbn.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtqvfmqske.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gtlvjqqqas.html

JS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gterrxyaqm.html

TS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtawmowyfs.html

Java: list.contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtswamzpqh.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtjuagjyba.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtykboadzh.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtuvgthmfx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hammf.cn/Article/details/gtgbmcgupj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.dashuyun.cn/Article/details/gtjgiueudn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yueranfly.top/Article/details/gtpttwowki.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtngxtajkq.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtsiyrhboi.html

Java: new ArrayList<>(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtgjfdzzgm.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gtxxueqblz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gtrlaetwqk.html

C#:   new List<int>(list);
来源：http://dali.cucudq.cn/Article/details/gtenbrgjsj.html

[D23] reduce 累积计算
来源：http://dali.guowangkeji.top/Article/details/gttvtwfrsg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtuydxtlyf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gtyqonvgpb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtwqobvubj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gtagbzssgi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hysaishi.cn/Article/details/gtyqzmgtsu.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtivemqxky.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gtoxszhkbi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtvjmntpsc.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gtdpvcncdi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtbpxwxvog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtxrzjcknj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhixingplan.top/Article/details/gtesxhsddi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtmelqazrt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtxpjjrfwh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtpmxjxwog.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtcgunzeyh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtvlgcuuni.html

[D25] Set 集合去重与交并差
来源：http://dali.chenzaomai.com/Article/details/gtefjcnbcx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhiwuduotai.top/Article/details/gtrhztatju.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gttilqvzrk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shzxlz.cn/Article/details/gtswhxxdsg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gtkxqmlywh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtfwryholq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtmnzjhytm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gzhubu.top/Article/details/gtdfjvhtib.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtyixxiedh.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtpjcefanu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtgmdkhzlj.html

PHP:  implode(", ", $arr);
来源：http://dali.wangdashe.top/Article/details/gthvezbjxd.html

JS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtrpizgriz.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtivfwpgbw.html

Java: String.join(", ", list)
来源：http://dali.c1oappe.top/Article/details/gtuhwdhinl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gthfpleuop.html

Ruby: arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcivqoseq.html

C#:   string.Join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtwuhjldss.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxnilmsqq.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtlebndneh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtoqzefqgd.html

[E01] 拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtvfktdvev.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gtaniqipbg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ehwqpu.com/Article/details/gtseiwbmha.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtkjixogvb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fengsongda.top/Article/details/gtbnaxfztw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.snrcjt.cn/Article/details/gtljaqbpoe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtiqqktxxq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtsfmvpzla.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtdmuohowv.html

[E02] 重复字符串
来源：http://dali.cqqwz.cn/Article/details/gtqwihcpvy.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoqbtogt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fzhhl.top/Article/details/gtgijbinyd.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gttixscwot.html

TS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtoqydyugk.html

Java: "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtclfsbher.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jyoumei.cn/Article/details/gtfnycdepa.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtxetkgint.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gogol.net.cn/Article/details/gtnsdneieg.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtxqtkaxvg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtrtcsgwsa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtoaaksbnx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtakkipiho.html

TS:   s.slice(1, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgoiwzoo.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gthrzinyvb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.bjfxy.top/Article/details/gtefsgejrf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtikrudcfe.html

C#:   s.Substring(1, 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtzbihaj.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtvpsjkgtw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tanke756.top/Article/details/gtuzvmbonh.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtftnajdcc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ppjwa.cn/Article/details/gtjbdoingb.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gtnchkynlc.html

Java: s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gthqffzxjv.html

Go:   strings.Index(s, "x")
来源：http://dali.xziqi.cn/Article/details/gtgbvehhyt.html

Ruby: s.index("x")
来源：http://dali.wangdashe.top/Article/details/gtptpzvljk.html

C#:   s.IndexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtzshltddm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.havefunace.top/Article/details/gtdxofilxm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtienoshbs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sufxvd.cn/Article/details/gtpqznzdkw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtpdvxfhgl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gthfucijgz.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtnavwidfr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtrrqfdaic.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtxxkqivyz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtpqpyhwoy.html


<!-- 参考信息 -->