代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtajqvuumg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gthdccttxd.html

Java: // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtwnmxltgy.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtinnzfhbs.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtcbktjcua.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtwhejcsxn.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtdspugoja.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtwamlcyce.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtcmnyhpbb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.vqdsnc.cn/Article/details/gtafcpyjch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gttwlfuglo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtthizndix.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtvhczrgan.html

Ruby: # 无重载：靠动态参数
来源：http://dali.snrcjt.cn/Article/details/gtgqvuejam.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtmtdtayxh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbjgcefh.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtjgdfmlyk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlgccsagz.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gthfekvyaq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhpnjmqo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ydzc1.top/Article/details/gtrzwzhjrc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtsrwyhglt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtdfjhvpaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtdyixqnlg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtgehppiwn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gtbfxsnevi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangshuangyany.cn/Article/details/gtfrkmkidy.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtjxezjlol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gticwtxuvb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtwwtqntfb.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtddkigwtq.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtkyntackq.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtdlhpijqx.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkdzqbfe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtwyeqjauq.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gtizthnvsh.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtknuoutuf.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtmaxomipe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gtwptmskvr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.redwolf501.top/Article/details/gtgpkdgnol.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtrrubdmtn.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtednjlfix.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtmujqvgwh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gtnzlyeslt.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtrunbagui.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtlevzhbnx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtbompseor.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtzwyvursr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoadcmelv.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtqhiqyhsd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtegcaoxmp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gthqzexomn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtfzlnukvl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtuwmqbodf.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gtwcuwrivw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtygtwpfvk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtuyardyjf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gtvykbbdrd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtqqvmpfnn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtvqyoccdw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtkmtoptga.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtrywevtqc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtrdplpizo.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtueokujpw.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtyvfkzuxn.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtqaskfihv.html

JS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gtgcdgptcv.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtbxrhzpgo.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gttsmqpaul.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtmccczklp.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtoygnxhbq.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtqdnrjjtv.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtwqoyrjgm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtdrubcbkt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gttrycrwdz.html

JS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtnudtouxz.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtydmvzkkm.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtlwiqmpoz.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtfpicpptf.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtebceeeyr.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtebzsmukm.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtdwakwuap.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtgmuvamuf.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtplhyunzt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtaqhtzhhc.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtwlgajwpo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuanzx.com/Article/details/gtyujehkht.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gtjemomwke.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtgzrtmgyz.html

C#:   a.Concat(b).ToList()
来源：http://dali.pycfn.com/Article/details/gtzmaaxmoz.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtoqwwaljv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtvgpinhgs.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtyqwwaxzj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtgqnluxhk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtkddpbvyh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtldnpssch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtchdbnprk.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gtzlzmdism.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdluopkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gtqpkynkoo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tian-w.cn/Article/details/gtnljoywov.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtflwmdgxv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtnvihhtcs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtbijxpjgp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtmanqfdhn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gthrnmltwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtszwkhjof.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtmqpcenzv.html

[D11] 反转数组
来源：http://dali.yj20258.top/Article/details/gtuuejfure.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.c1oappe.top/Article/details/gtqpjgyslp.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtywwmgvle.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtbwwlvdxo.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gtfpttqedn.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpmnlchp.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258.top/Article/details/gtgztitizw.html

Ruby: arr.reverse
来源：http://dali.ydzc1.top/Article/details/gtrgdsnqbu.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gteywputhp.html

[D12] 查找元素下标
来源：http://dali.9152youxi.cn/Article/details/gtvanjdmws.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gtvebcaaqu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gttsobembk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtrcdgvscj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtubqpamqu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtwoygyxef.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtjzmddxai.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtypqjiitl.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gturubdlwm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtnmmjnzae.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtjmhxxmwq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gtmaeziqcp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtvjkikuet.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtbdmywxxr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtreqnghjd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtxtiowzbb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtrpqqxhaj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sweek.top/Article/details/gtfzvxqmzs.html

[D14] 映射转换（每个元素变形）
来源：http://dali.c1oappe.top/Article/details/gtitdtdobj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yongpay.top/Article/details/gtngnftqsg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtoxthhpga.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndnkrcht.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtusdiotzw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtniqfmwlx.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gtupzxxgim.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtttgzhqpl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtpjovxmjd.html

[D15] 去重
来源：http://dali.tian-w.cn/Article/details/gttiqqwnzm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfswnnkz.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gttqgfxtia.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtsnjglgmv.html

TS:   [...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtlohcnvix.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hfpthk.cn/Article/details/gtattsnmov.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gzhubu.top/Article/details/gtaolijcfb.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtqvmwrcdu.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gtmoipmnry.html

[D16] 求和与平均值
来源：http://dali.chenzaomai.com/Article/details/gtaomasipa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjuzrcriq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuxming.cn/Article/details/gtbbprquoe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtftgienjr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtoqquqojj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtmqrohlks.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtnvukrjqa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xylfe.cn/Article/details/gtvuigzkai.html

C#:   list.Sum();  list.Average()
来源：http://dali.hnqzz.top/Article/details/gtweswctmi.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gthetgtorl.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtzbuwtgbs.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gtvdopwsha.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gtcfggkhft.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gtklhenneu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hnxiangtu.top/Article/details/gtgimhywwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtmukaucfr.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtcildcacd.html

C#:   list.Max();  list.Min()
来源：http://dali.dianchejie.cn/Article/details/gtfiwobchv.html

[D18] 扁平化嵌套数组
来源：http://dali.hammf.cn/Article/details/gtxpcdhzfd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbccvyxo.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gtjwceyfng.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.wangdashe.top/Article/details/gtcfnhypyd.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gtbpjokrwa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cdnleiting.top/Article/details/gtcwotalch.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtjzwktkqd.html

Ruby: nested.flatten
来源：http://dali.yuanzhike.top/Article/details/gtvcdjhteo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtoqrfvqsw.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtxzvmugwu.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gtxnjlptds.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gttizbboku.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtkamuqgzy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtemryiffc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guowangkeji.top/Article/details/gtdgfoapwu.html

Go:   // 手写 map[string][]T
来源：http://dali.yonumen.top/Article/details/gtktlsyimg.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xylfe.cn/Article/details/gtnzoattji.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gtaxvusnng.html

[D20] 统计每个元素出现次数
来源：http://dali.daria6918.cn/Article/details/gtgiempupp.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiinzuwe.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gtbbutqrgk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtfzuvagfc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtkshlvjja.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtmoxcjmjh.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gtkmtyzslc.html

Ruby: arr.tally
来源：http://dali.pycfn.com/Article/details/gtufaqkrha.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gtkwlebuqq.html

[D21] 判断是否包含某元素
来源：http://dali.jinqigfzy.top/Article/details/gtctrwlljc.html

Py:   x in arr
来源：http://dali.pycfn.com/Article/details/gtgzriemar.html

PHP:  in_array($x, $arr, true);
来源：http://dali.haohaochexian.top/Article/details/gtygkypzln.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtfjtnkdfp.html

TS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtnmnxlort.html

Java: list.contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgslybzcz.html

Go:   slices.Contains(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtbihimukl.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnejkbijf.html

C#:   list.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtgruyamgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hfpthk.cn/Article/details/gtbocskmmm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlkmjpoid.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nwbrower.top/Article/details/gtkhhrawxr.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtljlajldp.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gtlelwuylz.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gtdbrbkxsp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gogol.net.cn/Article/details/gtgzufcevd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhongyouzk.top/Article/details/gtjzwgdaco.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtxemcznsx.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtsjbalfsi.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.andypj.xyz/Article/details/gtqmupgqgy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hfpthk.cn/Article/details/gttfjgzitz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtrqgdrqrr.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuxming.cn/Article/details/gtarqwgdab.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ydzc1.top/Article/details/gtgyyldjlt.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtrqzadpyf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sweek.top/Article/details/gtsezasewv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtoajfpxns.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtphevshoe.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gtswihjvji.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sweek.top/Article/details/gtnwcsjhyn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtlapoitjc.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.meibo888.top/Article/details/gthdgdlgkh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtffxgmhxg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gtcjaqziqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtluisqfiy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gtgxyznayi.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gtynbtojxn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xziqi.cn/Article/details/gtzvnnshge.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtxakigvxw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtjhluczof.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtpcxjmdca.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtqdbptedk.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtycjpidox.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqimydji.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxubwptyb.html

[D26] 数组转字符串
来源：http://dali.zdqjudy.top/Article/details/gtqrweaxre.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenzaomai.com/Article/details/gtzcscewwz.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmruyqkbq.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtiuchnmfv.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtnervljng.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtiqvkgkay.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gaohongyu789.top/Article/details/gtaxxlxxdt.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtrkeusqaq.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtmqcofhit.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtturcliqa.html

E. 字符串处理
来源：http://dali.daria6918.cn/Article/details/gtswhindnf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtljffigxs.html

[E01] 拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtonokuuze.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj202588.top/Article/details/gtaikunpxg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtzwvzuuwq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxinkj.top/Article/details/gtjawaapze.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtqkfkrahh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuanzhike.top/Article/details/gtpykbkoce.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gtrqddtgsz.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daxiang520.top/Article/details/gtgkfpjnfl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gtttiwxddo.html

[E02] 重复字符串
来源：http://dali.tian-w.cn/Article/details/gtwbxjieol.html

Py:   "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gtivxktepf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgufenzy.top/Article/details/gtwvcjzmgm.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtfqegudga.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gthzoyzomv.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gttqllbzji.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.iojbl.cn/Article/details/gtslquvfbb.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gtmijezdxi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jqgufenzy.top/Article/details/gtcxmfhbck.html

[E03] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtbkaaqweq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtpjkesair.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtptdfovlj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtcnlewbem.html

TS:   s.slice(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtphcbibtl.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtpeesagcr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zycfv.cn/Article/details/gtdultwewu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ehwqpu.com/Article/details/gthwijddrw.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gthtuozbfc.html

[E04] 查找子串位置
来源：http://dali.ppjwa.cn/Article/details/gtldvdtjoj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtlvtldqxo.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gtrprmvrox.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigfzy.top/Article/details/gtlgphcgrz.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijkzqwub.html

Java: s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtqxfyzywj.html

Go:   strings.Index(s, "x")
来源：http://dali.tian-w.cn/Article/details/gtzwwijrmd.html

Ruby: s.index("x")
来源：http://dali.birdmap.top/Article/details/gtdjajxclx.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtqowsqizj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gttgrhqghy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gthggvidnj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtgzmsaqbr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenlongwang.top/Article/details/gtrlveoodz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zycfv.cn/Article/details/gtxyfcjimw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmooquln.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.gzhubu.top/Article/details/gtkchbmdqh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.kuanghao11.cn/Article/details/gtaoygqzlv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtyundhwbi.html


<!-- 参考信息 -->