代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtihhykfol.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihktwoop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtablyvtbh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.iojbl.cn/Article/details/gtwrkodhov.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gttkvzroen.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtaegirdds.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtgulsfgkb.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtzsuopfww.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtekqnnizv.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gtqnxyjjkh.html

[C16] 函数 / 方法重载
来源：http://dali.nanxuanxn.top/Article/details/gtbaistacf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtmuuolygz.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvwqbzgi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtjjpjgjet.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gtdoanwynr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtnwrbokrk.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtgmkmgcyk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtmtlgdmjx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwsnutngy.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnbhzdyth.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtdyjpickf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtovzubljx.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtfjbizpvp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtrgdhkcto.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtmrgnchpj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtmalesids.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkimjgoib.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtursbgpgv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.birdmap.top/Article/details/gtupiyvght.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtmbfdcqcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gthwwfollc.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtimwobpfu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtfduigecp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gttrvydmld.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtklishzzx.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtqpgdaytw.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvxkhljx.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtbybxxfew.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sufxvd.cn/Article/details/gtyjemkvfa.html

C#:   list.Add(4);
来源：http://dali.guowangkeji.top/Article/details/gtyypasdic.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzrcxtye.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtrwshanpf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtoggitove.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gtipxjzzvw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtngrvrjjp.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gttvmwvkjs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtxdpnlssz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jiagoushi.top/Article/details/gtnwhlnfiv.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtlraycdsb.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gtbgmfitup.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gtkxguwqgd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtcheeqjep.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yonumen.top/Article/details/gtbyhoiajc.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtdohvubsn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtplfpkted.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtjzqwyldu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtkxnwdrds.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtvxwxhoks.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtbgkezqlu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtzsyjnmhz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtirmclcwi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtvqakhlec.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtnlbvmtzz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtkfekiwua.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtmspidgyq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtqtoutojy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtnrfkaokf.html

[D06] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtdyzddjrv.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtmgztkqid.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtgldysbja.html

JS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtrbrahvtd.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtflubrrey.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtmtjokiyb.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gtgssfzkoc.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtdlimeuqw.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtddbtkhyg.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtlkplplvj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtefwrigwl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtgzrzonjf.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtwqnsmclz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtuorjloma.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtwbvbwssf.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtztlatmtl.html

Ruby: arr[1, 3]
来源：http://dali.0kj1m.cn/Article/details/gthqxdttid.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtvmjgdssw.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gtqqrptwyw.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtluznvjug.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxpeitky.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tianlin.xyz/Article/details/gtdzfdnshn.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gthrdkrgsr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtuimhywez.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtekityjdt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gtyznoldpc.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtlshvqoqx.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtgofmpmag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtpjsbieht.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtxntrovmb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtzvahegal.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gtcfnurnir.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gtujykolvp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtoqroqdbs.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtmnpocmua.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtshhsnqcr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtduwqmdmg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtrcxgljzs.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtayyzicss.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gticnjkklc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtxfridjyi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigfzy.top/Article/details/gtnazidsge.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.havefunace.top/Article/details/gtaifycpye.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtnscicmiv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258888.top/Article/details/gtejspuwex.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtsczbhulb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtyvnedcuy.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtavounwlk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtpbitldnl.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gttylnitfa.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebcrknwz.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gtawtiiigr.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtipealmth.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gtlrdzljkj.html

[D12] 查找元素下标
来源：http://dali.hysaishi.cn/Article/details/gtkdxyglye.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtgdizphdg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtbzebplek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtoawhufcd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zdqjudy.top/Article/details/gtgmfttqvv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtojwqgtoe.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtoysniqhf.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztmluciy.html

C#:   list.IndexOf(x);
来源：http://dali.bjfxy.top/Article/details/gthegjezrs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtokhywtxp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtqzuhqcoj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtqgvyibgz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.haohaochexian.top/Article/details/gtbwbongqw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtnagjjptq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtcskmcvsh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtibxhhonb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cheryme.top/Article/details/gtkhqxmkdh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtnyigbvbi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeyvaama.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtzrlytbnu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtavogzrto.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpruyepra.html

TS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtoyeprqmz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtldgedbug.html

Go:   // 手写循环
来源：http://dali.redwolf501.top/Article/details/gtjfbpagmc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtwgnbtpun.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtutkdwddg.html

[D15] 去重
来源：http://dali.shuidangran.top/Article/details/gtoovpztpn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtjhxwtkwz.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtgahmzoyh.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtfmhetjug.html

TS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtxueorgql.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtmwqptiww.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxwmqybw.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtiuyyllhf.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtaoyceiol.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gtmkxudgpf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtkzhpatvf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtipjxyjld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiegteqh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtrrjrvbml.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gtmxffbwbv.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtkmmjwesc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shzxlz.cn/Article/details/gtxevwnbzc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigufen.top/Article/details/gtbqxplrlz.html

[D17] 最大值与最小值
来源：http://dali.tanke756.top/Article/details/gtyfaqgdgr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagxahuvu.html

PHP:  max($arr);  min($arr);
来源：http://dali.shuidangran.top/Article/details/gtgxtqvunl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtczjpjveh.html

TS:   Math.max(...arr);
来源：http://dali.gotoacloud.top/Article/details/gtgilbwnrw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtlhwryqmv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqlfzeatc.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtdvnzktym.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangtech.top/Article/details/gtofevdiaj.html

[D18] 扁平化嵌套数组
来源：http://dali.yueranfly.top/Article/details/gtxgkukspz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gtoiusgtvj.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtgehgtfve.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yueranfly.top/Article/details/gtcusngfqt.html

TS:   nested.flat();
来源：http://dali.havefunace.top/Article/details/gtthcoxhfj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfizlsuk.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezhtjgyt.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtpiardlqo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtildpxfbq.html

[D19] 按字段分组
来源：http://dali.xziqi.cn/Article/details/gtorippwkw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtyeozvwsh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhixingplan.top/Article/details/gtmhmtdhym.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yvedp.cn/Article/details/gtqwbzcpud.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dianchejie.cn/Article/details/gtfgyldlcr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtpsgtnkzi.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtmxjaghds.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtjioiuyzf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aibaodan.cn/Article/details/gttkupzhyy.html

[D20] 统计每个元素出现次数
来源：http://dali.tianlin.xyz/Article/details/gtacykajgq.html

Py:   Counter(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzxusyxq.html

PHP:  array_count_values($arr);
来源：http://dali.cqqwz.cn/Article/details/gttaahrttu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusflracp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gttevisawa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.kuanghao11.cn/Article/details/gtqmgvxdsh.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtbqvshxlj.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtcggomhko.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.vqdsnc.cn/Article/details/gthtgxhvot.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gttwilbxhu.html

Py:   x in arr
来源：http://dali.zycfv.cn/Article/details/gtnjjjtgxb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.redwolf501.top/Article/details/gtmbyvohiy.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtkpkcgqed.html

TS:   arr.includes(x)
来源：http://dali.havefunace.top/Article/details/gttgmkzduw.html

Java: list.contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtjespxnlj.html

Go:   slices.Contains(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtrowfycpy.html

Ruby: arr.include?(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtdoszwpty.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnhmddur.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtajvanhcl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yueranfly.top/Article/details/gtzulhwiay.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtudluogoa.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yuxming.cn/Article/details/gtidijnarp.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtqjqhnvfh.html

Java: new ArrayList<>(list);
来源：http://dali.chenlongwang.top/Article/details/gtvawmdcpi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtqavfgwrf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gtnwqvhhti.html

C#:   new List<int>(list);
来源：http://dali.0kj1m.cn/Article/details/gturkylldx.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gtsddaxxdf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtfknxupom.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pycfn.com/Article/details/gtebowainn.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtldtxyrpm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gttqlvcnty.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.pengpengdd.cyou/Article/details/gttcofwwfs.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gtcfyilubw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.fzhhl.top/Article/details/gtdsmyzebb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.haohaochexian.top/Article/details/gtfaatorpd.html

[D24] 字典 / Map 基本操作
来源：http://dali.316326.xyz/Article/details/gtuyjacxxc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgfzy.top/Article/details/gtvpcflfrd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtumuvwxnk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guannengcc.top/Article/details/gtbzzcozqt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtpikzqybr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hammf.cn/Article/details/gtgtzbrmth.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtnpevmyqg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtkgcwutnp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gthypjkyfz.html

[D25] Set 集合去重与交并差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsifgyeo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.kuanghao11.cn/Article/details/gtrfbodpbm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cdnleiting.top/Article/details/gtksymwrsb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtwhhnwdbu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.snrcjt.cn/Article/details/gtoezarmwj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.0kj1m.cn/Article/details/gtazuoqvpq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtypitfdmo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtptyitudb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cqqwz.cn/Article/details/gtcqfdeehn.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezgrwnid.html

Py:   ", ".join(map(str, arr))
来源：http://dali.quarkkingdee.top/Article/details/gteqzzffrs.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gttehlqfyp.html

JS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtdybqerfq.html

TS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtbntrnmvz.html

Java: String.join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gtiyqxvfaw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtlszsnvcl.html

Ruby: arr.join(", ")
来源：http://dali.jianghu66.top/Article/details/gtitlmyakh.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtsdjxputf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmyjwwewt.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtquzlbids.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtwgrlfecz.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtedisjtii.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtxdewebtu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gtpvtaemjx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtvyajipli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtwxcvwiak.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvshclvah.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtddiadljq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gtixqhgogh.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtyddrgttl.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtqsjtatws.html

Py:   "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtyukvpkoy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtwjkuovzi.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtqytjpmhs.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtveulcnbz.html

Java: "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtiyapqshc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnqbmypzk.html

Ruby: "ab" * 3
来源：http://dali.quarkkingdee.top/Article/details/gtwpcbsiop.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtewmvldyl.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtmvocepox.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.316326.xyz/Article/details/gtouklfuwr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gthdaesiqt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtkgthawzq.html

TS:   s.slice(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtvrodwkvy.html

Java: s.substring(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gtjtcvohgb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gttukxodda.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenjidiqi.icu/Article/details/gtqpsotyik.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gtcdxwwphm.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtjvxwasxw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtijqspoiy.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gttmjmmdje.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtndsudcgn.html

TS:   s.indexOf("x")
来源：http://dali.birdmap.top/Article/details/gtvopaddnr.html

Java: s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyjoagwd.html

Go:   strings.Index(s, "x")
来源：http://dali.xuanzx.com/Article/details/gtkmwixlqy.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gtejkpgnen.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtfylfrguq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbmkrieh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gtponywzct.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjkrzrrp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtkwvthryh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtcnpmpkud.html


<!-- 参考信息 -->