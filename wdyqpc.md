代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2pcmneoey.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gt2jkttruqp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2rahdopza.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gt2umlekzrg.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2ypyzljkw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gt2cvokxtuq.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2ktmcpbis.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2rlnvbsjo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gt2bnzlrevv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gt2ghzpvbum.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2elgvpyzx.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2glohdfgb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gt2gnygtymk.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2oafejfix.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gt2padkjobo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2aavspdjh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2alwfiyfj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2kiwconta.html

Java: // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2oqbpmjnz.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2ruhvozuu.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2bvostlou.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2eeeezmav.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cysqylbp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2xqqtmnsr.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2pggyjlus.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gt2ojfatdet.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxhyyjne.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gt2oswsqqwv.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gt2wlayjcvw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.iojbl.cn/Article/details/gt2cnadiiez.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tmsnkbdk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2nlmvsjoy.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gt2leaefqbx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2iivanjty.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gt2iupcxzan.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2kizufdjr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2ivuuwaer.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2vfqidrqt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzevjokz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2dkbjcizx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2iwkylexx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2mykmelmm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2flpabuol.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnuhfiol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2lycllizy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gt2rofckfbw.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gt2jfwbdnqg.html

TS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2hbmbcrxl.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2aguqjyyx.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gt2xsivqkpy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2lqeguags.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gt2iajhyjzd.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2mnispwmj.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2bbfqxpsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gt2avmmhita.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2awqrerrt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2izdkubcg.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2jtjngkxf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkkbevbj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ybcxt.top/Article/details/gt2ahuiuvrr.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2jukptmdt.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2stpewadz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gt2pfshivll.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2xnudhdma.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2kaprvtgj.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2fodhowef.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gt2ipqmuwol.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nanxuanxn.top/Article/details/gt2omlufyex.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2rljvxizo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2xzvnbteh.html

[D05] 访问与修改元素
来源：http://dali.jqgfzy.top/Article/details/gt2koityvij.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkrkfgvh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2gvjwmjhu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2qrchijsb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gt2baqeklal.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gt2xgzepkek.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gt2gvngehnt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2wdcnqihc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2vibobfvn.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gt2qzcuwiuf.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2bphsgelo.html

PHP:  count($arr);
来源：http://dali.yongpay.top/Article/details/gt2eexkadyx.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2dogxyomu.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzpkyqrv.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gt2murzuoqu.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlpuirka.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gt2jaavoszz.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gt2lrpjhqzd.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2frpebjob.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gt2eamvoevq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2ilgnmtyw.html

JS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2fehyxycv.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2yboidhdd.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gt2nvpaplcu.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gt2bxobhrei.html

Ruby: arr[1, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbttmifz.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2soqlgxij.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gt2flbcdeqe.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2csivctqp.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gt2kluregzy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gt2tuvkkjbn.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gt2cxayespg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2cgtattcd.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gt2kxaccayp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gt2noyubuof.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmuowjge.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2coyackaz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gt2csflvjwk.html

PHP:  sort($arr);
来源：http://dali.ybcxt.top/Article/details/gt2pvdfovfo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxuanxn.top/Article/details/gt2ztzlfrxj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xziqi.cn/Article/details/gt2rtgjzfnx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2keejuhdj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2rnjifnel.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2ekwcyvse.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2myaelead.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gt2gbvcwumg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2nczoaair.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2diolhykd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gt2wxharstd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2brproewv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gt2wojgtzcq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tian-w.cn/Article/details/gt2krldofrs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2uacfeayh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2khjnstla.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gt2idmyxkoj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tianlin.xyz/Article/details/gt2jfzwjjab.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2tqxxobzf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cqqwz.cn/Article/details/gt2rbuznmoq.html

TS:   [...arr].reverse();
来源：http://dali.hfpthk.cn/Article/details/gt2hnvvcpln.html

Java: Collections.reverse(list);
来源：http://dali.c1oappe.top/Article/details/gt2csnuwhlb.html

Go:   slices.Reverse(arr)
来源：http://dali.xuanzx.com/Article/details/gt2wtyiksfy.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gt2zoslwegp.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2uihoeutv.html

[D12] 查找元素下标
来源：http://dali.xylfe.cn/Article/details/gt2sutrrgnf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwccnylo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2vfwuapeu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2qsskyzky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2ronzvhkc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gt2rxqrijqo.html

Go:   slices.Index(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2urwvtfkd.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2iosayoou.html

C#:   list.IndexOf(x);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqhdzrpj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2jiqylqnf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpexseyq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258888.top/Article/details/gt2cvdxlwkk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2wdvvjvym.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2zqexnbqz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gt2elgtqnjh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gt2qzuqnedp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2bxcnggbr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2aucnrbsw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2blfgnhgn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gt2atsapxoq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2khiiuwtf.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2ebtnagws.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuloxbar.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2ajzcvzxb.html

Go:   // 手写循环
来源：http://dali.ehwqpu.com/Article/details/gt2erbpukau.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2xcyauixx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2niocsmcr.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2musranrg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2ewrrtqlj.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gt2gvpjvxbw.html

JS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2znsfjaoa.html

TS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gt2odielajf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.mhx1999.top/Article/details/gt2wcttnhuu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.meibo888.top/Article/details/gt2cnmeyboe.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2blbgsfex.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gt2fehybspz.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gt2vsdypvee.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwezzomg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2urlmcljo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpsvtosv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2rzefsuig.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gt2upknnpin.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2fyexaxsh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2vwriesbk.html

C#:   list.Sum();  list.Average()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixcoygvs.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2xielkjbr.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2cclmizad.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2kppfoljf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gt2xxsgyrzy.html

TS:   Math.max(...arr);
来源：http://dali.hnqzz.top/Article/details/gt2jvpnbokv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gt2iojvkidf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2utnnufhd.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2yamxcreu.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gt2gdqjaqwd.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gt2xmsuynfm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gt2vieymdlm.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gt2bnllgtzu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2khhrewrc.html

TS:   nested.flat();
来源：http://dali.vqdsnc.cn/Article/details/gt2jdsndacr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2onbhfejb.html

Go:   // 手写双层循环
来源：http://dali.xylfe.cn/Article/details/gt2tybiicup.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2dbaxlqtn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2ftuusnlw.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gt2vypwinku.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gt2opugxzkz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenlongwang.top/Article/details/gt2cjpukgcf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.cqqwz.cn/Article/details/gt2lkjvuusc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2sienstie.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.c1oappe.top/Article/details/gt2dcyiqcvt.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alrypzfl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zycfv.cn/Article/details/gt2kxmwdxcc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hywenlv.cn/Article/details/gt2dnbrotys.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gt2reidlepm.html

Py:   Counter(arr)
来源：http://dali.xylfe.cn/Article/details/gt2mnorvpol.html

PHP:  array_count_values($arr);
来源：http://dali.nwbrower.top/Article/details/gt2efrsbtwo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gt2fouoshlt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gt2whblpnpp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gt2hrpwatpx.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gt2ljssiarl.html

Ruby: arr.tally
来源：http://dali.hammf.cn/Article/details/gt2xuskytpl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hfpthk.cn/Article/details/gt2piuwciio.html

[D21] 判断是否包含某元素
来源：http://dali.nanxuanxn.top/Article/details/gt2otutuxdp.html

Py:   x in arr
来源：http://dali.yueranfly.top/Article/details/gt2asgicshb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xktmbtmo.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gt2vbwhdsui.html

TS:   arr.includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2yzfzbrku.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvfzia.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2bjasxmca.html

Ruby: arr.include?(x)
来源：http://dali.316326.xyz/Article/details/gt2rorxztwu.html

C#:   list.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gt2jtkfoqvc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.vqdsnc.cn/Article/details/gt2uwzczssq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gt2vuwmpqhi.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gt2zxruidaz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258.top/Article/details/gt2nbvpuuya.html

TS:   [...arr];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbetvrap.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gt2oljekbzc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tanke756.top/Article/details/gt2kvypkjot.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2tmjuiopz.html

C#:   new List<int>(list);
来源：http://dali.dashuyun.cn/Article/details/gt2sfbafmnq.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gt2aalzaqlf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2aeycwent.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nbeunwup.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2wxlkkcke.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zngaueqm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhengqikj.top/Article/details/gt2nelobhel.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2onlvjwug.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ydzc1.top/Article/details/gt2ikkfysqq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.sufxvd.cn/Article/details/gt2shkogihz.html

[D24] 字典 / Map 基本操作
来源：http://dali.havefunace.top/Article/details/gt2wsouuvdb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.daxiang520.top/Article/details/gt2hmttajle.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zdqjudy.top/Article/details/gt2bnudrptv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2kwfeyqye.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2umimeqhr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnntxdyb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ybcxt.top/Article/details/gt2cuuisrgb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gt2jcpxiqqf.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.snrcjt.cn/Article/details/gt2lbhevzmu.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2chopnrjb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gt2ycgwsueu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gt2brgkcnkt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2apwbogpe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gt2fgvbeafx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gotoacloud.top/Article/details/gt2arvkzjsc.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fzhhl.top/Article/details/gt2jgpefvpk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2dhsijfnq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gt2qxwfptco.html

[D26] 数组转字符串
来源：http://dali.xuanzx.com/Article/details/gt2bithwavc.html

Py:   ", ".join(map(str, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yptlwint.html

PHP:  implode(", ", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2iruoitcp.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2vvghqevo.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2iwsvmgcw.html

Java: String.join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gt2itljhyxk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.tanke756.top/Article/details/gt2gztccpqz.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2zwxapszp.html

C#:   string.Join(", ", list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynuboyxq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xxmhfowa.html

E. 字符串处理
来源：http://dali.yanxiufei.cn/Article/details/gt2foxliwvl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rzjrievz.html

[E01] 拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2skbqsjno.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gt2lthsbacb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gt2wtvxpfac.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gt2onscfdbt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2dfnstaju.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jotgeroq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gt2ezzsfxkn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xziqi.cn/Article/details/gt2vrikllic.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2lmqslypc.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ielqpyov.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gt2hzohxdco.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenzaomai.com/Article/details/gt2rstlzntf.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gt2yeqpwlhg.html

TS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2izkwvbax.html

Java: "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gt2vkkgcduh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgjybpgx.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ludeyuac.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gt2fmlpgfrf.html

[E03] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gt2duovfnlz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2brsscfnp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzytlvgo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yonumen.top/Article/details/gt2belbagnt.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2unmlkplt.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2vspmnqdl.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dashuyun.cn/Article/details/gt2asalswas.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.redwolf501.top/Article/details/gt2asgdzsgt.html

C#:   s.Substring(1, 3)
来源：http://dali.jinqigufen.top/Article/details/gt2tjtvpupw.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gt2erxctzrg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gt2tckdqgzp.html


<!-- 参考信息 -->