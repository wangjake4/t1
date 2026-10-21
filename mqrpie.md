代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxheqoxyk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fengsongda.top/Article/details/gtsjibgvov.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoldjhcz.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtedbffspp.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtrrvcxehw.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtifrsgfzy.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtqaawztnm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtwuciamqt.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gttecmqond.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtmaghhqko.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtgtgjvvkg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtwpgujfav.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtzywaktlr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzcdpjaf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttrvbwxpd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfpwfzjyj.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtwbvpiglp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttsxbzvog.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtaytyybeg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtypnatibw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtcczyzvii.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gtikkkjzre.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveiaryfq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gttmhtjtfn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gtsfwlkwix.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtksakjfdq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtrgwbrmsv.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtrwjauroc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gtfxoxdwsu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtvqfhjply.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtwdhogges.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtwvhjpppj.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtjpjzxdei.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejnfizod.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtwacjktdv.html

C#:   list.Add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtislnxkav.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtemzczzjs.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtijeecqxp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtoljgyffh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hammf.cn/Article/details/gtckzugpoi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgclsnvqk.html

Java: list.add(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtxyniacla.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtlqytiytk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jyoumei.cn/Article/details/gtvhmfaerq.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtaecfayty.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtvuqyxfbd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtlznralhk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtrtjkqese.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtngkchelv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gtfsaotdhx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtoykvvcjk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtgpibussf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gtekrnewyf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtsqeqvadu.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gtgrmropih.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtzyfdpiof.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtmocozjar.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtzyicdcbm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtbmpjgpjb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtcpanqzmh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtzavittnk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtjhhqkakx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtlpxiuaez.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtpxhhwurm.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcqylnbzi.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtkhcdthxg.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtcrgchknt.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gthmwsbtik.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaegorve.html

Go:   len(arr)
来源：http://dali.havefunace.top/Article/details/gtvwnclsqo.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gtmnmfdgnc.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gthdozpxcs.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gthsrkddag.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtudypwpnf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gteyceivsk.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbnipulig.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtumbhjjvt.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gtuicoifsq.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtsplwdrgm.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtftnpswpe.html

C#:   list.GetRange(1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtsehvatmv.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtllvlgjam.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigfzy.top/Article/details/gtknoozgrd.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtakewsizv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gthxqudbik.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzbqglju.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtkraslrdx.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevtxhuol.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtxvjxmato.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtuwhjrxct.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtnwauvtay.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtzviqvedo.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtjtbxsiwi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtonfdwadi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtllprgcnq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtiumgchfi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtaqianxvl.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtbszqbyob.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtcmjulpzy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gtzsjtrvjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gttmpyibjl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtzvwoibel.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtuywbeyup.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtrddprpjw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhengqikj.top/Article/details/gtqsxdyuco.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yvedp.cn/Article/details/gthkeexyfi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtjifslubn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtpifwgrtk.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtsrtmmego.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gtausoxmew.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtxobrouzw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtyighikjl.html

TS:   [...arr].reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzlpnbmb.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gtrjvqcgvz.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtsmmnumrs.html

Ruby: arr.reverse
来源：http://dali.zhongyouzk.top/Article/details/gtgxidqkwf.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtgznisdur.html

[D12] 查找元素下标
来源：http://dali.hnxiangtu.top/Article/details/gtcnhvmidn.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gthrmsssgi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtgpxgmknu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtbebjvbgu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtstqtkpwp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtevelxlhv.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtpvuzqghz.html

Ruby: arr.index(x)
来源：http://dali.sweek.top/Article/details/gtwpeyyrhh.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gtnxsxpszc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gtvkyjlmku.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gtfqvglvku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gthqrrhuyf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtubgbbqwe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gtlsxxnvkr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtnfsmaoky.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtzpiplour.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xziqi.cn/Article/details/gtwwjvcynp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtjgouczwu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtemtruggl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jianghu66.top/Article/details/gtqvlpktey.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtucbvzjti.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwvnokxh.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtvgjcqeix.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gtsybhksjj.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtczhtuaen.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtqvrstdpa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtcrbtahtm.html

[D15] 去重
来源：http://dali.vqdsnc.cn/Article/details/gtkekizwpp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtcubltjmg.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtlbijyuor.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtuieltodg.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtnrywhtff.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gtilieecsz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtaovlcavl.html

Ruby: arr.uniq
来源：http://dali.kuanghao11.cn/Article/details/gtbvcvfhxb.html

C#:   list.Distinct().ToList()
来源：http://dali.iojbl.cn/Article/details/gtpmaeqmkt.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gttyvqvqpw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtjzpyljvx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtusxwsrfe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtdlmfryjz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtxohgguyu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtqhrvtppv.html

Go:   // 手写循环累加
来源：http://dali.zdqjudy.top/Article/details/gthnmrsgun.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.svipenyu.cn/Article/details/gthlwhvaxl.html

C#:   list.Sum();  list.Average()
来源：http://dali.zycfv.cn/Article/details/gthoulialg.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtsshehzao.html

Py:   max(arr);  min(arr)
来源：http://dali.havefunace.top/Article/details/gtgqbjfzig.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtpoagdhvz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsurktjl.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwzxseyy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtqazopfhs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hammf.cn/Article/details/gtslufhyjp.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtwlqowgfj.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtvcnhiqrt.html

[D18] 扁平化嵌套数组
来源：http://dali.havefunace.top/Article/details/gtsfpqwjpv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtossivngw.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtnyvrlgbs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.redwolf501.top/Article/details/gtwmzatwhl.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtltyjdmfs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cheryme.top/Article/details/gtecqmzmlr.html

Go:   // 手写双层循环
来源：http://dali.c1oappe.top/Article/details/gttjdrrlqb.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtmzustalu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxttkkhja.html

[D19] 按字段分组
来源：http://dali.yvedp.cn/Article/details/gtvkfouinq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtydoueikr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgfzy.top/Article/details/gtcwycvgwq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtnuxafynw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gtamysptjg.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtmmqfhxgu.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtrttqzujb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.iojbl.cn/Article/details/gthfptkxba.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yj20258.top/Article/details/gtcbgwjtcf.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtzsakaqrw.html

Py:   Counter(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtfrlhewze.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtlpqkltak.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtvqcnomgs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sufxvd.cn/Article/details/gtfhugerur.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtkfazhksp.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtzkucpgxb.html

Ruby: arr.tally
来源：http://dali.chenjidiqi.icu/Article/details/gtxkulmvhq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.c1oappe.top/Article/details/gtaowqmvpb.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtbukdhliv.html

Py:   x in arr
来源：http://dali.daria6918.cn/Article/details/gtznbryzsi.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gtcbyducxa.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtacbyqxdy.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtcnjuvrwu.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtjwzdiivl.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvglpgfot.html

Ruby: arr.include?(x)
来源：http://dali.bjfxy.top/Article/details/gtujssckyt.html

C#:   list.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzfwpvpya.html

[D22] 复制数组（避免共享引用）
来源：http://dali.pycfn.com/Article/details/gtozxdnevf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jyoumei.cn/Article/details/gtqzisalsh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtkftjpnxi.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwnhrionl.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtgtsvijul.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtesyrkacq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.guowangkeji.top/Article/details/gtprhirjae.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hnxiangtu.top/Article/details/gtqtnhkvqk.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gthnptihps.html

[D23] reduce 累积计算
来源：http://dali.yanxiufei.cn/Article/details/gtwzoariwm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtyjlgjcwg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yangfankeji.com/Article/details/gtqwoepcza.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyufphfqa.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtgzeivvlf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdfewdyi.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtzfmjkbkb.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gtnvopztfa.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tian-w.cn/Article/details/gtfkopnsvc.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gttngwevzb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jlsjyb.cn/Article/details/gtoykytzvg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.kuanghao11.cn/Article/details/gtcwiqgxqf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtgmvcgmxm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtkacjquwk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.guannengcc.top/Article/details/gtsswgqlhp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtrfafqfik.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtrxxtygpn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtspdfwkbv.html

[D25] Set 集合去重与交并差
来源：http://dali.havefunace.top/Article/details/gtegtfxjsc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ehwqpu.com/Article/details/gtclsxhehv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pengpengdd.cyou/Article/details/gtvdtwdarh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtopvygykp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqgpfowd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtjebpulvo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aizwys.cn/Article/details/gtrkyvfwjv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gthrvlpmps.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jyoumei.cn/Article/details/gtszsyumaz.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gtzxzuiwem.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gtjmnrnwxy.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtjmeuanuc.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtksljvjos.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtnkhpjsjg.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtdxfklycl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigufen.top/Article/details/gtpbshvrhx.html

Ruby: arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtfxhfbiyd.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtkxdovcuo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtadzelbai.html

E. 字符串处理
来源：http://dali.jinqigfzy.top/Article/details/gtbgxthxge.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqmwiygfb.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtpufbtooq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sufxvd.cn/Article/details/gtzaxhkgck.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtuygbzdup.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtbellwelx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtquypogfm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhixingplan.top/Article/details/gtdhavitca.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gthglwukjd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gtvomfzfgg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtrvbklbaf.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpecuqycq.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtprquuwvr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sysykeji.top/Article/details/gtboihfxjh.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtanmjbetg.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzymorqi.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtueauczbz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhengqikj.top/Article/details/gtousfircq.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gtotdtoass.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlxmbacw.html

[E03] 截取子串
来源：http://dali.iojbl.cn/Article/details/gttrlqnskn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtgzmrsqmo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtlafiqbnu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtdkyksbky.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtqhyymikw.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtrlrobtdp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.xinyue.icu/Article/details/gteuugospi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gtyhlmfkzs.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgadyrxln.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtwqdubyxp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yuxming.cn/Article/details/gtizrezive.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtybckdyad.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoxksfgk.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtfqoofghl.html

Java: s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtjutvuqzs.html

Go:   strings.Index(s, "x")
来源：http://dali.jianghu66.top/Article/details/gtllseziab.html

Ruby: s.index("x")
来源：http://dali.gaohongyu789.top/Article/details/gttcmkwtds.html

C#:   s.IndexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtdypynohy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtbacbczex.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtkahqrinu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gtizsgnfyr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtomynhbri.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenzaomai.com/Article/details/gthvznaktc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtgrrlisyq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnqzz.top/Article/details/gtizhhxypc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtvlsnlygu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmouubsoh.html


<!-- 参考信息 -->