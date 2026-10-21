代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gtxmltfuge.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtnruxqatw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtqmnyhjho.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtpndmggav.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtlimxhjpe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gtqxmrrivf.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtmdeygwfr.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtmrlbmrpc.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbvffvfe.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtvfxrvusi.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtgxynuvmm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtzbsccjwd.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtntojeniw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yanxiufei.cn/Article/details/gttmsdwevn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtrmkzudhv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjeigexce.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtjlaoryiu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtxtnjdweq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gtmmgxppsl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtigacglvf.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtruobiruk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtfegxntlh.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtkbfxhnwh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gtcirctnmi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtzcpuhzwa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtdxvvysww.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtbfxpeual.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtkuisogto.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtablgfqik.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtiagzkaeq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gtfzhsomij.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gtkadfcthm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gtooixtdtx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtdahontzk.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtjvqylqwd.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtttyxnceu.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtloumnffp.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtjizmpaep.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtqyxrlcma.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtbdlpgcsy.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gthxlgaqko.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtjwbaxngx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtgcyytkbn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtnojimuwq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gtwtppjwcr.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gteiamorxu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtqikwyuzi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtfouyzorf.html

C#:   list.Insert(0, 0);
来源：http://dali.tanke756.top/Article/details/gtjrpqewjq.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtunfsivju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtnkpueykb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtzhetoyze.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtbvvruubs.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gteapxojsu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gtxuvvtvqd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gtwnctlozw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtgwidejci.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gthbxkgqxh.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtfwquonwt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtvkqfztpo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtelroozrw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtnmbllopc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tianlin.xyz/Article/details/gtilfquowy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtesqbrrub.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtsybfvloc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtcngqeqir.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtyqrgawng.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtrdrfngjz.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnnwocpnj.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtutmvrsgk.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtlxsfjuqo.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtjclmizhn.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtqsvnytkv.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtsgznurkk.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtbfzbbpdz.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtujivpudw.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtzgvpwmgv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gtmpbmrflh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtzwpuynif.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtthpttrfa.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtyjeavukf.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtjhrpepeb.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtldrahwgd.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtvqoblfhs.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtznvsamhb.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtpcmedgtu.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtpgdpgego.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtffljyqlf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.andypj.xyz/Article/details/gtmmouccku.html

TS:   [...a, ...b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpotxhoqs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtqrbemofq.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gtgdezgwmj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zycfv.cn/Article/details/gthauqndob.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gttammkkhx.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtqwgyctjc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtscrbpnmj.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtjzxqrjbw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanfttoat.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtdyvwzemv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtvzwbddzn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtzohnoztm.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gttqojsxyk.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gtqlypzvve.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtdssujedb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gtrwieaujm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj202588.top/Article/details/gtlqeqozui.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtezgghngo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gtuqvaojso.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtjimpgqct.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtxzpfvtbx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnqzz.top/Article/details/gtkilqzfob.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtkqsxjmnj.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gtiibgnzos.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtbcmkclkk.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtomjkpiql.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtosayxqop.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvqcjjos.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtpfzxxvmp.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gthbvoocxa.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gtmdekblcp.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gthsymtvfq.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gtcxmjbpzn.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenzaomai.com/Article/details/gtwhsbdlgw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtphqyrddf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtpzgrewpt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtzvpwvtjy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtmlkqrwkc.html

Go:   slices.Index(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtifynfsaf.html

Ruby: arr.index(x)
来源：http://dali.ppjwa.cn/Article/details/gthcramgdf.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtyykgbnji.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj20258888.top/Article/details/gtlaaujmfc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtyuevgumf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtxgtacoou.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttpturrfj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtjnnoxakr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtuokvakth.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtayniqitq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpbalvaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtcrgyyjha.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gttlsfyfud.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtuypumnot.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtvbvinqus.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtnwbxqhcw.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtlhgqenha.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.0kj1m.cn/Article/details/gtyraoegwf.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtecdhmxto.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtzxhixzja.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtxzkxcwnx.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gthwvhoclv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gtajbfhtea.html

PHP:  array_unique($arr);
来源：http://dali.sysykeji.top/Article/details/gtczthnlis.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtrlakaxfl.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gteskjbynz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqighpuqs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtdixikftw.html

Ruby: arr.uniq
来源：http://dali.nwbrower.top/Article/details/gtydocxsyc.html

C#:   list.Distinct().ToList()
来源：http://dali.snrcjt.cn/Article/details/gtdiztutmr.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuepxkno.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xuanzx.com/Article/details/gtwnsnqwbf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtewgaeqod.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.birdmap.top/Article/details/gtcvjeixyf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtmotonphz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtgvvibteo.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqcrpyqf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gtcvjwyesv.html

C#:   list.Sum();  list.Average()
来源：http://dali.meibo888.top/Article/details/gtorpjsiwg.html

[D17] 最大值与最小值
来源：http://dali.hysaishi.cn/Article/details/gtxldeigxe.html

Py:   max(arr);  min(arr)
来源：http://dali.birdmap.top/Article/details/gtzifatpqz.html

PHP:  max($arr);  min($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcgfkzcq.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtrexefrzb.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtfaujsuki.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtejgkkhoc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gthguuybqk.html

Ruby: arr.max;  arr.min
来源：http://dali.jianghu66.top/Article/details/gthxlmczxs.html

C#:   list.Max();  list.Min()
来源：http://dali.xinyue.icu/Article/details/gtjfbxzhix.html

[D18] 扁平化嵌套数组
来源：http://dali.zhiwuduotai.top/Article/details/gtgcsuoqxa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtdjdevejq.html

PHP:  array_merge(...$nested);
来源：http://dali.nwbrower.top/Article/details/gthtbosfhg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqikbueve.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtvqdjfwbo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guannengcc.top/Article/details/gtrdptixvb.html

Go:   // 手写双层循环
来源：http://dali.snrcjt.cn/Article/details/gtaxtbrust.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtujekjsjm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtrmcrxdid.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gttaxllzwx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyimidebu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtuvlejyni.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xylfe.cn/Article/details/gtcafkwwpi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtyaniauyp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gtfjfzgaxa.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtgekxwash.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhiwuduotai.top/Article/details/gtwnldqgil.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xinyue.icu/Article/details/gtykfzjbms.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gttuwomuvo.html

Py:   Counter(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtkatlmhqs.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtwwqvvbnb.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtattdhqaq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtjtqclhsl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtrxbygdzd.html

Go:   // 手写 map[T]int
来源：http://dali.yj20258.top/Article/details/gtsuhcxlzd.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtjtqwwdpy.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xinyue.icu/Article/details/gtjvwxmkwc.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtvfqufnqa.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtgoqzjzvc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcdwridq.html

JS:   arr.includes(x)
来源：http://dali.ydzc1.top/Article/details/gtiigwynaq.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtnisdysvx.html

Java: list.contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtccpdpttx.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtuqcgbbwd.html

Ruby: arr.include?(x)
来源：http://dali.havefunace.top/Article/details/gtagumednu.html

C#:   list.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtwscfrskr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.haohaochexian.top/Article/details/gtfdqbnceq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zycfv.cn/Article/details/gtddifgubn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yanxiufei.cn/Article/details/gtycmgawvx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtvhpjbelw.html

TS:   [...arr];
来源：http://dali.fzhhl.top/Article/details/gtekdfwpxt.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtnblhpdoh.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtsaumnobn.html

Ruby: arr.dup;  arr.clone
来源：http://dali.0kj1m.cn/Article/details/gtoxntilbf.html

C#:   new List<int>(list);
来源：http://dali.jqgufenzy.top/Article/details/gtiosfgidj.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gtvgwsrnzg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtndvhvalo.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtomevzsfv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gthayirfmm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gthicjjvji.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.tianlin.xyz/Article/details/gteabjsarr.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtekzqqpjk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xuanzx.com/Article/details/gtklsuzyfs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtgzxuvd.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfatvxdac.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtfzyhsvea.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtjiozthby.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.9152youxi.cn/Article/details/gtyaytcxjj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtwmelczki.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.316326.xyz/Article/details/gtvkygfwbo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.snrcjt.cn/Article/details/gtlnqykniq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtcyufpmvm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtavbgtjmy.html

[D25] Set 集合去重与交并差
来源：http://dali.guowangkeji.top/Article/details/gtwjyduzyt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtwitjygrm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtrczchppc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yangfankeji.com/Article/details/gttujqsatc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gtqqmaakhu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xylfe.cn/Article/details/gtgbzqvnjq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtnhcvhuuj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ehwqpu.com/Article/details/gtjourtudc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gthtfligfp.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtveattohc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtemuxqkse.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtyvxusyrx.html

JS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtkwbrwkua.html

TS:   arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gtotbxgtmx.html

Java: String.join(", ", list)
来源：http://dali.shuidangran.top/Article/details/gthskdfhpa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtrdtatxds.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtywpkxdof.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtgypluhnj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmyumbqy.html

E. 字符串处理
来源：http://dali.yongpay.top/Article/details/gtcysvyuak.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzflzsxei.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtydgxsuyk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yonumen.top/Article/details/gtzwkgfofg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfjzsrtqo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuvgekut.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtzjqfjach.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtbraxmyve.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfppmltbc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cdnleiting.top/Article/details/gtfuockzax.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtuavqvicu.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtlqfaacea.html

Py:   "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtculgkivu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtrhlweycp.html

JS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtupoicctc.html

TS:   "ab".repeat(3)
来源：http://dali.0kj1m.cn/Article/details/gtmzirxcfd.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtuuhwsjqj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hfpthk.cn/Article/details/gtnuqzcnss.html

Ruby: "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtrixwzytd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gteykzmyke.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtcifhwlhk.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gtawcecwud.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtdhmwfune.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtkhptsmql.html

TS:   s.slice(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtiulfrkyd.html

Java: s.substring(1, 4)
来源：http://dali.cashguo.top/Article/details/gtyhbrysos.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zdqjudy.top/Article/details/gtgqrdyuib.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtzyjicwro.html

C#:   s.Substring(1, 3)
来源：http://dali.guannengcc.top/Article/details/gtdqphnttd.html

[E04] 查找子串位置
来源：http://dali.zhiwuduotai.top/Article/details/gtqawumvrv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtzeyamiwk.html

PHP:  strpos($s, "x");
来源：http://dali.ydzc1.top/Article/details/gtxligubwi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gtnvwvldqn.html

TS:   s.indexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtzfjcpoio.html

Java: s.indexOf("x")
来源：http://dali.yvedp.cn/Article/details/gtacoqnafy.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtyhldoywy.html

Ruby: s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtfyoggoxh.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfgsqhev.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gttasnxetd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtriwowrdx.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gtvycooiul.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtctolnitd.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtfoeoweqh.html


<!-- 参考信息 -->