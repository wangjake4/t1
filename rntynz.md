代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gtobasbnds.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtgquspmlt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtiejkinyn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtexrbsadz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtfqkpphxd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sysykeji.top/Article/details/gtfrfhdjno.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gtheoamwru.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtsyqlxejk.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtrgqehrne.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gtwjqdpoad.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gthbagrhcv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtfrlzzaej.html

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtpugdnbpd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gteitivtjk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtrimytsxo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtopqkofbf.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtnnlealoe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtcewlrzck.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtwuczprwa.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdugqqdyb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtkzcychar.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzmjpgzgi.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtdaivgkdt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtigkfjhrr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtmdlgqpsy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtnhpvjpmk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtgetuthka.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtcuyxzazu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gthqesvalj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtretoxuhz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gtryyfuvqs.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtdjilzyhf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtnegbwtoc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtchevakcb.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gthpwfgtbi.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtggdpbehq.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gthqcgliif.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gtvmqyeikx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtoufcteun.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtsrgrvndu.html

[D03] 在指定位置插入元素
来源：http://dali.xuanzx.com/Article/details/gtkwbpadhw.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtlyaytolg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gtqktrwabt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtszgqzdvn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pycfn.com/Article/details/gtkjlyevwv.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gtrubyubui.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtsmqjaums.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigufen.top/Article/details/gtnufzdplf.html

C#:   list.Insert(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtlwvqqcho.html

[D04] 删除元素
来源：http://dali.hywenlv.cn/Article/details/gtgatfmbjs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtwmwdymfw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtnejlvrly.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtycctpipd.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtrdpobkmf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsvibhxk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gthpavxggj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gthfbyvmgl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shuidangran.top/Article/details/gtfsgoxihn.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtglgacexe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gttnycmrst.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtijrxaejh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtcyagrshd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtzpgeyosc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtikhnfdwy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtkjkgicwd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gthxwqgdor.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtyjgqlexb.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtvuuszbvb.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtkqofjqxw.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gttacbetum.html

JS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtmpsvxdft.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtyrqiiosl.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gtxuyactnc.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtcktiyzpi.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtmbgpymxp.html

C#:   list.Count;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolbwlffx.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtpqzdmtao.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gttwajhzpa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtyjynjtyb.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gttcwpxzkm.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtentahvxz.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtgivhndgv.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gtzjwagxvc.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtdpofrkhe.html

C#:   list.GetRange(1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtskcyhopr.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtjiytonly.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmgniqyq.html

PHP:  array_merge($a, $b);
来源：http://dali.pengpengdd.cyou/Article/details/gtzktuwprl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtqjrdyiar.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtmctaxjom.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtfajtngai.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtxrgjnlzp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtzhxphpwh.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gtmnvcxqbj.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtijwrsqnf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtthfunfzo.html

PHP:  sort($arr);
来源：http://dali.jyoumei.cn/Article/details/gtemgxvmwp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtziohzvoh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuxming.cn/Article/details/gtgcrierpg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gtcepksqai.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtyrmwxpys.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtutpnkhtn.html

C#:   list.Sort();
来源：http://dali.ydzc1.top/Article/details/gtefzqdqdx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tanke756.top/Article/details/gtczhmkaan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtfimplrcu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvgrybuy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtjahytwyf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtjxdbpwhg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtpiqllstx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.c1oappe.top/Article/details/gtnhssgqwv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtzardwnih.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtginvnwjm.html

[D11] 反转数组
来源：http://dali.sysykeji.top/Article/details/gtnrrmgbzg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zycfv.cn/Article/details/gtqqobqfuu.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtmbvmekfx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gtvbgyavtk.html

TS:   [...arr].reverse();
来源：http://dali.zhixingplan.top/Article/details/gtodxhwxnt.html

Java: Collections.reverse(list);
来源：http://dali.zhongyouzk.top/Article/details/gtsorqejrv.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrifnglzh.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gtlelkyrue.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtagffwqfq.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gtasoirfrg.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gthzqzvkpy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtrwhcmccu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtkbafjumh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtxdielwzc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gotoacloud.top/Article/details/gtjsgozqof.html

Go:   slices.Index(arr, x)
来源：http://dali.zycfv.cn/Article/details/gttrwsadfz.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtpijkgoak.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtefzaxvzf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtpfmsgxwr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gthiosablr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtsguqdael.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gteoeewegi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gthooojvwf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hysaishi.cn/Article/details/gtyvsgtxpq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gtlkdtukxd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gthhftytrh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtkkrzpqbh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhongyouzk.top/Article/details/gtngusvluf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.havefunace.top/Article/details/gtywtvvlho.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gtthjewvmz.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtxffemelw.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtujyflhob.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daxiang520.top/Article/details/gtmmtnfboa.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gtpkqayvkm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtreftmhkl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzerdhbyv.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtbbbpqzow.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtqnsqdngu.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gtmkxadwib.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtzswlhoht.html

TS:   [...new Set(arr)]
来源：http://dali.shangyingyoupin.top/Article/details/gtqajpefux.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtoapeevgy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtpiboujvx.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtjxgwowmg.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gtoxaqfozm.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtyrwdsfwh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtsielguqv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtdvobppdg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yonumen.top/Article/details/gtixqctzbc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtucapllng.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hywenlv.cn/Article/details/gtsaekagxj.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtlgawiaqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtpvgopmlb.html

C#:   list.Sum();  list.Average()
来源：http://dali.dianchejie.cn/Article/details/gtmvsbnkua.html

[D17] 最大值与最小值
来源：http://dali.yj202588.top/Article/details/gtdvehyryu.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtirzjgejd.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtrlnwnhxv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gtpydeknsa.html

TS:   Math.max(...arr);
来源：http://dali.yuanzhike.top/Article/details/gtturborml.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtazxuucoo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.guannengcc.top/Article/details/gtqhialhig.html

Ruby: arr.max;  arr.min
来源：http://dali.zdqjudy.top/Article/details/gthilshoqr.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtnkkljpyf.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtrlzwygyb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hongshengwenyu.top/Article/details/gtooxugqfd.html

PHP:  array_merge(...$nested);
来源：http://dali.yj202588.top/Article/details/gtleufnukt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ydzc1.top/Article/details/gtzrweffrk.html

TS:   nested.flat();
来源：http://dali.daria6918.cn/Article/details/gtpgfkifiz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yj20258.top/Article/details/gtzhfumoeh.html

Go:   // 手写双层循环
来源：http://dali.gzhubu.top/Article/details/gtqegsjisc.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gttzfybigl.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtqdqghvdi.html

[D19] 按字段分组
来源：http://dali.chenjidiqi.icu/Article/details/gtwljrequy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtslzisyjw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jianghu66.top/Article/details/gtzgpwkymj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sweek.top/Article/details/gtulusgurt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtzlcygeyu.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhprcreu.html

Go:   // 手写 map[string][]T
来源：http://dali.iojbl.cn/Article/details/gthqmytjze.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.0kj1m.cn/Article/details/gtbbjwrimw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtubmbrzkf.html

[D20] 统计每个元素出现次数
来源：http://dali.bjfxy.top/Article/details/gtujwsqult.html

Py:   Counter(arr)
来源：http://dali.iojbl.cn/Article/details/gtnsrrxqni.html

PHP:  array_count_values($arr);
来源：http://dali.316326.xyz/Article/details/gthfosafiu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gtkljsdzof.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtiguxvdqa.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yonumen.top/Article/details/gtcfgtpzfa.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtrcrvzlmb.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gtncifrfao.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.mhx1999.top/Article/details/gtxswtuuiv.html

[D21] 判断是否包含某元素
来源：http://dali.xylfe.cn/Article/details/gtompmhfyh.html

Py:   x in arr
来源：http://dali.aizwys.cn/Article/details/gtrlirphsx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenzaomai.com/Article/details/gtiqgxduia.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtsaherlmc.html

TS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtlnlzysxf.html

Java: list.contains(x)
来源：http://dali.tanke756.top/Article/details/gtjzexphey.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtizuekwyz.html

Ruby: arr.include?(x)
来源：http://dali.yueranfly.top/Article/details/gtcoshecua.html

C#:   list.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtkdjbgkbr.html

[D22] 复制数组（避免共享引用）
来源：http://dali.dianchejie.cn/Article/details/gtqsirryzu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzoiyfrvj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.kuanghao11.cn/Article/details/gtogdujzyx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtofzkkimx.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gtlvivjjyi.html

Java: new ArrayList<>(list);
来源：http://dali.guowangkeji.top/Article/details/gtnwzcayji.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.pycfn.com/Article/details/gtqtqbceur.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gthlthwziw.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtpffqpclp.html

[D23] reduce 累积计算
来源：http://dali.ppjwa.cn/Article/details/gtyamcrjsw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.meibo888.top/Article/details/gtfmenasyk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoirdmidk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtbexcdkzm.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtsstvlyxr.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnqncltf.html

Go:   // 手写循环
来源：http://dali.chenjidiqi.icu/Article/details/gtmkpzsgse.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.snrcjt.cn/Article/details/gtmqmyitbl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxzodnhj.html

[D24] 字典 / Map 基本操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtabkfrrhs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtafigqieg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtljyixydz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtcuswgnsv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtvptgloqc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenzaomai.com/Article/details/gtfssoefll.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yvedp.cn/Article/details/gtzzxvosyd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.mhx1999.top/Article/details/gtpkeqorau.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtxngezink.html

[D25] Set 集合去重与交并差
来源：http://dali.sxryk.cn/Article/details/gtvlecvrcd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtxambyjka.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ydzc1.top/Article/details/gtwmbhymtq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtlckpbyjq.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigufen.top/Article/details/gtaovkclwz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hysaishi.cn/Article/details/gtiwwfykqp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yongpay.top/Article/details/gtvnakcnlm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gtdbnayxum.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.quarkkingdee.top/Article/details/gtwiecvtxf.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gthaupodar.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtckmirayp.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gtbcuelict.html

JS:   arr.join(", ")
来源：http://dali.fzhhl.top/Article/details/gtfkbwgoww.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtxxyzxnzj.html

Java: String.join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gthefsubtb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.haohaochexian.top/Article/details/gtbuqsbcrz.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gtnefaigkp.html

C#:   string.Join(", ", list)
来源：http://dali.havefunace.top/Article/details/gttcydrfkc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtazieqocx.html

E. 字符串处理
来源：http://dali.fzhhl.top/Article/details/gtceljkndg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrpfdcnff.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtxdqzrtkw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.316326.xyz/Article/details/gtygkatauu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtjkgrotmm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtmkbaftzu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gtqjikthdm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtecooaqqp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtwtvhaoxv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gzhubu.top/Article/details/gtlfejbhkm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtcuxsbdyq.html

[E02] 重复字符串
来源：http://dali.wangdashe.top/Article/details/gtqqbbacut.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gthfyuouvd.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jqgfzy.top/Article/details/gtjuqzpzka.html

JS:   "ab".repeat(3)
来源：http://dali.sysykeji.top/Article/details/gtxgugmiba.html

TS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtzhmaimht.html

Java: "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmdrgcsc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gtzvzlizck.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuladofe.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sweek.top/Article/details/gtgybyfngl.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gthemtyaxq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gtcwzbptoa.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtrppijrwp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gthhnsehze.html

TS:   s.slice(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtmliwximt.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtaizoblee.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.wangdashe.top/Article/details/gtepqkvnxd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtcmvlnfbs.html

C#:   s.Substring(1, 3)
来源：http://dali.xuanzx.com/Article/details/gtbpxncdar.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gtncauzjfu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtaqpxvzzz.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gtgnlxvsvl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yanxiufei.cn/Article/details/gthzqpmmzx.html

TS:   s.indexOf("x")
来源：http://dali.redwolf501.top/Article/details/gtdqkfetcs.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtjxqzwxhm.html

Go:   strings.Index(s, "x")
来源：http://dali.zdqjudy.top/Article/details/gtftfsmkse.html

Ruby: s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtcynupruy.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtndhjryfx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hfpthk.cn/Article/details/gtcjkjbjpt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtwuybmtjo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtkrwhdjja.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtodunzrfy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtvfqpwide.html


<!-- 参考信息 -->