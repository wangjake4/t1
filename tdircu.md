代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtjezvmzua.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtyvluneqy.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtrwwlzqek.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpyoerkm.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gtublbgude.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxvdsvje.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtjxvzefax.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtnjubpzgv.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtoqewegdj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdexzgqog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtybbxzztv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtovthchnc.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtlsxlgeno.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtafudekqh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtjpfvpryn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtiajiuues.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gteiprbogi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgavvynqz.html

[D01] 创建数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtlvfibvyi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtkrqnmcqa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtzrtdoxie.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gticqdgpzf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gtnrshlwtz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtvbwjdods.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtyijkwosp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtbecceyyb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtcauhaude.html

[D02] 追加元素到末尾
来源：http://dali.cashguo.top/Article/details/gtpgqsdeti.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtfxjddavw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtgsawkshz.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtyryscbdq.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtmwylaohf.html

Java: list.add(4);
来源：http://dali.sysykeji.top/Article/details/gtjpjutbxt.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gttywmfbat.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtngmsbphs.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtoaqiggur.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gtosrdbyzm.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtdjsimbif.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtutubiumm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtqgopzecr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtybazrjgb.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtanbhpdim.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtnzdsyocg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtkpiqrhfg.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtjmevcdyr.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtxqjqpkaz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtjisecioq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtclymyzfr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtkoppmzip.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtzraamgfd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.9152youxi.cn/Article/details/gtpskzconk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gthednttwm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtfnbhftvi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtzociecpo.html

[D05] 访问与修改元素
来源：http://dali.fengsongda.top/Article/details/gtxlbaapta.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtsjneasbb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtmxarajdh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gthqfmwrjl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gtifzwgugo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gtqjuygbtp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtgcqlzuke.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gtgvvppzzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdebghzr.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtmspqbsqp.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtlgufobbz.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtrpbsimbw.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdojudsw.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtmtuibiqh.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtdgfguufu.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtywacxoxd.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtpgpbhmvw.html

C#:   list.Count;
来源：http://dali.yongpay.top/Article/details/gtdbogvbft.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gthwkgwrht.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtguxfujtc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtunihqukc.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtzosrxwtm.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtzaizaekn.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtwtwgrgkq.html

Go:   arr[1:4]
来源：http://dali.sufxvd.cn/Article/details/gtrgprmcik.html

Ruby: arr[1, 3]
来源：http://dali.9152youxi.cn/Article/details/gtrmncvorp.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtturiiwkd.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtkpmnludb.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtcizapxvi.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtdoiblcwd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.havefunace.top/Article/details/gtkbmmhdee.html

TS:   [...a, ...b];
来源：http://dali.yj20258888.top/Article/details/gtvymoxdwj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtvzpuzvpm.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtcvhwftro.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtnnxtiobf.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gteuhknhlr.html

[D09] 排序（升序）
来源：http://dali.iojbl.cn/Article/details/gthcnkauqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtdpcwmntr.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtiuwsdmpy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gtmbcezoan.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtuhyjqlob.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gtfrgikiun.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtimsqsyqa.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtuypoqdem.html

C#:   list.Sort();
来源：http://dali.pengpengdd.cyou/Article/details/gthvcmfmjq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xylfe.cn/Article/details/gtuvxosxib.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj202588.top/Article/details/gtxxgeagkw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtupueqatl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtfinpgvsv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gtzayndhhq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtcjzvnrdf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmevssht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gtqgrxluci.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtnymjqgsv.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtxyxwxakb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtosbggz.html

PHP:  array_reverse($arr);
来源：http://dali.yangfankeji.com/Article/details/gtlhsaqsut.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.c1oappe.top/Article/details/gtnkftdtqy.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtfsrnlhkt.html

Java: Collections.reverse(list);
来源：http://dali.gogol.net.cn/Article/details/gtydiygrbn.html

Go:   slices.Reverse(arr)
来源：http://dali.fengsongda.top/Article/details/gthkxahttg.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtbzmotuoc.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gtvpjfeqbn.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtfbboqllb.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtawxwmcre.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.bjfxy.top/Article/details/gtdlhylhdo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xylfe.cn/Article/details/gtzoesiarj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsdsvdla.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtuxhpxtol.html

Go:   slices.Index(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtsoebsvmt.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gtbjqcizpv.html

C#:   list.IndexOf(x);
来源：http://dali.yj202588.top/Article/details/gtvirmawnm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaacsnfmj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkigbtgaf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkeynima.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtwitwpzyh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gttacnufss.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtjjrxtxls.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtoyoolwvv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhengqikj.top/Article/details/gtfucaxwtw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtijmvdqij.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtxmgszmaq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtivtkdrng.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shuidangran.top/Article/details/gtdppyzwvk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtwkaoxezx.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtutsazsvd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtrknglvlu.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtrqrdaygn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtnxcqilod.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtpthqzsjk.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtzufdjsoo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtapjuhtxf.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gtdgqwusmh.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtxojmpzka.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtipdmplxd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxuanxn.top/Article/details/gtdjqakkwq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gtxyuxwwfk.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtrveqjoqu.html

C#:   list.Distinct().ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtucufrpxm.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gtibbwewav.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtchzfxrhf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtejuovjii.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtalasajik.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shuidangran.top/Article/details/gtojieufra.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhongyouzk.top/Article/details/gtooldmqzw.html

Go:   // 手写循环累加
来源：http://dali.yj202588.top/Article/details/gthyboieyd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhongyouzk.top/Article/details/gtikulmkro.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gttdxbzejo.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gthzcfpqrw.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtttkynyxi.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtfngxeays.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtaqmvrnfe.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtbvvlwdeq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zycfv.cn/Article/details/gtigjkzrtg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtxqflrecf.html

Ruby: arr.max;  arr.min
来源：http://dali.aibaodan.cn/Article/details/gtpojqcxvv.html

C#:   list.Max();  list.Min()
来源：http://dali.hammf.cn/Article/details/gthiukrtnw.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtnxgklzqp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtkmwssmpt.html

PHP:  array_merge(...$nested);
来源：http://dali.nanxuanxn.top/Article/details/gtypfwglrt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gtggwwvysa.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gtrvwdcxrx.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtufnohjyl.html

Go:   // 手写双层循环
来源：http://dali.bjfxy.top/Article/details/gtxhmdhskl.html

Ruby: nested.flatten
来源：http://dali.jiagoushi.top/Article/details/gtroeebgcr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gteazyousq.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtexxegcfx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.guowangkeji.top/Article/details/gtfhfbzivv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtymcgxitf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtdreydjto.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gtcdpqvvas.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtexqhumkr.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gtcqnfixjq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtykseyqoh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hysaishi.cn/Article/details/gtqqsettlf.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtmhlgytrb.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbzlzcgn.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtagknqalf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxuanxn.top/Article/details/gtxqnoarmg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gtgntqnbqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtzezecocx.html

Go:   // 手写 map[T]int
来源：http://dali.jinqigufen.top/Article/details/gtdufcnuox.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gtjpymijtl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shzxlz.cn/Article/details/gtjhbopnup.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtnfcjvkjd.html

Py:   x in arr
来源：http://dali.bjfxy.top/Article/details/gtxhumdxfy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.fzhhl.top/Article/details/gtsizrjsjp.html

JS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtjpsvzdhg.html

TS:   arr.includes(x)
来源：http://dali.meibo888.top/Article/details/gtefegzwfd.html

Java: list.contains(x)
来源：http://dali.tian-w.cn/Article/details/gtiagoabsi.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtwcjdpqlf.html

Ruby: arr.include?(x)
来源：http://dali.zdqjudy.top/Article/details/gtlmgypjwa.html

C#:   list.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvadixbje.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gtpzzqnvbt.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxinkj.top/Article/details/gtlhcbtctb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jiagoushi.top/Article/details/gtqgbbrioq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtogghbqcd.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gtcwajwnlu.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtoruhsczg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xziqi.cn/Article/details/gtvqvpqyqd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.pengpengdd.cyou/Article/details/gtzmpxqxuk.html

C#:   new List<int>(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtyebkacmb.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gtjvvrrexf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gttjvrdwry.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cucudq.cn/Article/details/gtsveymris.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgfzy.top/Article/details/gtjrtbvtxo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtogzvnovp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hammf.cn/Article/details/gtirhmsrtf.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtsdlfwtza.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hysaishi.cn/Article/details/gtyfbdopvb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yueranfly.top/Article/details/gticrxtbil.html

[D24] 字典 / Map 基本操作
来源：http://dali.c1oappe.top/Article/details/gtqcmzoamb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtiaekpzgb.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtulwbydmj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.vqdsnc.cn/Article/details/gtnurdftur.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtzgwzahik.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinqigfzy.top/Article/details/gtpnhinwwt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtlmjuqlqk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hammf.cn/Article/details/gtnlxdelcw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtfnmwuixd.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gtombzataw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shangyingyoupin.top/Article/details/gtcxjjrxmd.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gtbshmtazl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxjuohmbg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtnfoqbivg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtidxegzfa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ivvv.top/Article/details/gtclmiihwt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jyoumei.cn/Article/details/gtjombhtvk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gthyfrjlcl.html

[D26] 数组转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtgpinhayy.html

Py:   ", ".join(map(str, arr))
来源：http://dali.tianlin.xyz/Article/details/gteldtihqe.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gtaubjsvel.html

JS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gthpsgxlgz.html

TS:   arr.join(", ")
来源：http://dali.xinyue.icu/Article/details/gtdwldyecs.html

Java: String.join(", ", list)
来源：http://dali.yj202588.top/Article/details/gtosmugvwc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gtkxhujfiz.html

Ruby: arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gtmxvmsbtp.html

C#:   string.Join(", ", list)
来源：http://dali.nanxinkj.top/Article/details/gtdygcubfj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtndhnifzj.html

E. 字符串处理
来源：http://dali.shangyingyoupin.top/Article/details/gtmvqebyyy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzannwuhx.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjpuifkic.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtszsvmojl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtcrgceeny.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtuxvrhktx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtvtymtamm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuanzx.com/Article/details/gtfhligzsz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtngewsuoq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtklwqbgey.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtkohqyovi.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtqwkncwik.html

Py:   "ab" * 3
来源：http://dali.c1oappe.top/Article/details/gtcktiyfet.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtwgjrjezr.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtkwdegypu.html

TS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtyprqydlg.html

Java: "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjvwufix.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gtqdskvlae.html

Ruby: "ab" * 3
来源：http://dali.zhoulong.xyz/Article/details/gtfstkqckb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhwzvxrn.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtvyypxnns.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ybcxt.top/Article/details/gtumldmvci.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gttaovqmox.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtqhphpjqy.html

TS:   s.slice(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtthfaxysy.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtbklmpqbw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhixingplan.top/Article/details/gtluakcauu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtkmaesspk.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gthushqinq.html

[E04] 查找子串位置
来源：http://dali.9152youxi.cn/Article/details/gtxbfjgseo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlnhubxf.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtmgwdrbtl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtmpczdgyb.html

TS:   s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gttpwvxjig.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtmqrcqjsh.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtigiapjqk.html

Ruby: s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtlxmwzpvk.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gthgkbuzpr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.birdmap.top/Article/details/gtofsjmmyc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shuidangran.top/Article/details/gtqgmjipmj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnybdrrd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jqgufenzy.top/Article/details/gtohikkfuk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gtygxtphrt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtwtfjhipj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtbdemmzfh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ybcxt.top/Article/details/gtuunccodx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.pycfn.com/Article/details/gtgtzununa.html


<!-- 参考信息 -->