代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtmauvbmbm.html

Go:   func add(a, b int) int
来源：http://dali.vqdsnc.cn/Article/details/gtkrkxjdwm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gthpgfhvwb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ydzc1.top/Article/details/gtscitxnyd.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtfzggeczh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtzuivoekq.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtrglpmsaj.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtssfpfroi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gturhoftol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gtrhavifvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtzgpiexto.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gtujslaalg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gtbgcozhmw.html

[C15] 解构 / 展开参数
来源：http://dali.ehwqpu.com/Article/details/gthmxlnrrr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtwqufhafd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtdiiaeezp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtsxdbesva.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtvzwhexfa.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtuqkmbhbg.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtebkfxhxp.html

Ruby: a, b = pair
来源：http://dali.sxryk.cn/Article/details/gtailtsgzt.html

C#:   var (a, b) = pair;
来源：http://dali.gotoacloud.top/Article/details/gtnajcwzva.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gtmsrjclek.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gteeyovwbv.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtnlhnkcif.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtvfolcfuf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtlhamwpaz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tian-w.cn/Article/details/gtamyzbqis.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtbiudogpe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyqtpmbj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtrwjldjni.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxhworzcv.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtkqrpuabx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwjplognm.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtasitmdjc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gttdcysylq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtpnonrfdf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtqykcucrx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.redwolf501.top/Article/details/gtcyytsqmu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtpvpxwxtp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gttcxfsfxa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsizanzo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtesjwnylf.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtjnhyzhoh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gtuuzmaiaz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtndymotbb.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtfebogdwr.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtbkhzfdlz.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtkzlhbjml.html

Go:   arr = append(arr, 4)
来源：http://dali.cheryme.top/Article/details/gteojofefl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtosmtuutx.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gthlmxfpat.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtcjgfloqg.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gttsimaczk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtsvjdizbr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ppjwa.cn/Article/details/gtvjkvdcjc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtteinneux.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtyaddswfh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtvbothrwb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtmuqplzkl.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtvxramonm.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gtastpxfdy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtyofamaeg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtqozefnqd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtkfgcvxii.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtqqgfwniu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtywiewiwc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtybnagdmk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gtsclojwcr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gttivfvopt.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxmfdvnm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtlspscjop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtqclqtuqj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtfnnkxlfe.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gtkpfmclxr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihjsicpr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtgdcpxneb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtalgxpwhb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtgilsehnd.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtincystgw.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtfohfubfy.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtzymzslqp.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtaowynaci.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtxzzqraga.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtkpoqzyea.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtnppvrvjw.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gthglqehvz.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtzbyzherk.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtvktbiflp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gtzmrdcvju.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gtrcdrkgfi.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtthfijzwm.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtvzcbrzzq.html

Java: list.subList(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtkonoqpgy.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtuizvzeqh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gthzntktho.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gtayopjqap.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtkhmriidk.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtbfmyscyc.html

PHP:  array_merge($a, $b);
来源：http://dali.kuanghao11.cn/Article/details/gtbuuqqckl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtxjvsepwm.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gthjlvhpja.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtuqqythni.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gtdkowciuz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtwutcoppa.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtcqeghsjz.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtlbslzrwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtuvwztvus.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtttfhmzwq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gtljomowtc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtugjenitv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtowqajxcn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtgppeswhe.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtjrklqbix.html

C#:   list.Sort();
来源：http://dali.quarkkingdee.top/Article/details/gtqafyenrp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.redwolf501.top/Article/details/gtewceckzr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbhbuojh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtpfscoqks.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtwbwbfkso.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gtapgdhgxu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtlnbpevjw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtggrjkaoe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtceljyyom.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtxzgqpkkn.html

[D11] 反转数组
来源：http://dali.ehwqpu.com/Article/details/gtehkjzqtw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258.top/Article/details/gtlzushvmo.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtedkkclks.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuanzx.com/Article/details/gtwfgxyuji.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtxxbdntqm.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtjrszvzlo.html

Go:   slices.Reverse(arr)
来源：http://dali.havefunace.top/Article/details/gthznivyls.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbqficdn.html

C#:   list.Reverse();
来源：http://dali.hysaishi.cn/Article/details/gtrojgsqnq.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtxsbqpwdq.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gtomwktaoi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.daxiang520.top/Article/details/gtcjktooyf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtoqruzalm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtlfuiibab.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtvqxrvpqh.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtblbrjake.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtidyfpghf.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtligaiscj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jyoumei.cn/Article/details/gtwazysjpp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtpqvpqrod.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtodwmkzfd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjthnwni.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtnzgvzyvn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtnbrajgoo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipvbltjg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hfpthk.cn/Article/details/gtdoopogpu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.c1oappe.top/Article/details/gtkhzayefi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtdcvmjyso.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtrvftmjtx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtyjclhhcw.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtbqcnwkwo.html

TS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtmmmdaehu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gtmtrhwqhq.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtdkvndblc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtaponwtbn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtgkwuutpj.html

[D15] 去重
来源：http://dali.hywenlv.cn/Article/details/gtynqshazp.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtubthxdfr.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtkswnxmsj.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtrzyddfbd.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtvrhaunyd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.snrcjt.cn/Article/details/gtzodyybsx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gtngtlpoug.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtjbieoncj.html

C#:   list.Distinct().ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwckokw.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtxbgjnxmw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtikjhjpou.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fzhhl.top/Article/details/gtsrlazrez.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtgbfcmiiy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtpjqjvulm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtfjyenakt.html

Go:   // 手写循环累加
来源：http://dali.jlsjyb.cn/Article/details/gtkidzubvh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtixvqenin.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtufhmofkd.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gteihfrcoq.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtwjwgimqn.html

PHP:  max($arr);  min($arr);
来源：http://dali.9152youxi.cn/Article/details/gtbehbqrjt.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gtxduspnyc.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtgqbnvisg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gtskiloggs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtrjetxvqa.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtxgmwwzqy.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnjtxbjg.html

[D18] 扁平化嵌套数组
来源：http://dali.daria6918.cn/Article/details/gtoazaquss.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtdtaffkes.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtkrxvbtbx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtfbvnjfmj.html

TS:   nested.flat();
来源：http://dali.redwolf501.top/Article/details/gteotcromi.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuveysqst.html

Go:   // 手写双层循环
来源：http://dali.tian-w.cn/Article/details/gtlgkfjlft.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobsdhdpw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtqnhxawhc.html

[D19] 按字段分组
来源：http://dali.yongpay.top/Article/details/gtaffjqazl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258.top/Article/details/gtfcfbuguk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtpxqykurb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gtsxztojop.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtnimgsubc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.vqdsnc.cn/Article/details/gtwhmkyqsu.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gtkstqrver.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hongshengwenyu.top/Article/details/gtzaukhohc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ivvv.top/Article/details/gtuvrsvdbg.html

[D20] 统计每个元素出现次数
来源：http://dali.gotoacloud.top/Article/details/gtdtlzocdr.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxiigxruc.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtftygrroa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunrmxspm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gtiqmghiqy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxuzpqbm.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtlonjfuml.html

Ruby: arr.tally
来源：http://dali.sysykeji.top/Article/details/gtjmxtnytz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhongyouzk.top/Article/details/gtfrqtfsjs.html

[D21] 判断是否包含某元素
来源：http://dali.gzhubu.top/Article/details/gtwmynsbrc.html

Py:   x in arr
来源：http://dali.kuanghao11.cn/Article/details/gtggsrhkzw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtryswunmq.html

JS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbouygrh.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtcntzhsih.html

Java: list.contains(x)
来源：http://dali.sweek.top/Article/details/gtycldmhmq.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gttrbtgkih.html

Ruby: arr.include?(x)
来源：http://dali.tanke756.top/Article/details/gtpfenjhqh.html

C#:   list.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtcedbifrh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtupdkbtwi.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.316326.xyz/Article/details/gtgxtyofpo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenjidiqi.icu/Article/details/gtcogzicnq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhengqikj.top/Article/details/gtwpsslkxc.html

TS:   [...arr];
来源：http://dali.svipenyu.cn/Article/details/gtsvsnuqff.html

Java: new ArrayList<>(list);
来源：http://dali.aizwys.cn/Article/details/gtesnlygbi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.andypj.xyz/Article/details/gtackxnknt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xuanzx.com/Article/details/gtputghlld.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gthlhdfijb.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtgmyqmgbv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yj20258888.top/Article/details/gtddxjqcwb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dianchejie.cn/Article/details/gtbckfrphs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhengqikj.top/Article/details/gtlfcnkjma.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtapkwanxy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtnjqiazry.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtcdgqcvrg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtxoywbtzz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhoulong.xyz/Article/details/gtyoqkgodh.html

[D24] 字典 / Map 基本操作
来源：http://dali.hongshengwenyu.top/Article/details/gtfwewuaxi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hfpthk.cn/Article/details/gtkgxgcfcu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.0kj1m.cn/Article/details/gtqcqhgmdz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtxnehggky.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtbxmnqhjy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.aizwys.cn/Article/details/gtgkjdsmnm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nwbrower.top/Article/details/gtvibajdfh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtqxolcfhl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gthxmxwbji.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gttytrygcg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.xuanzx.com/Article/details/gtwjvdzasm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yangfankeji.com/Article/details/gtmughkubd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtuskemhyp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gtzervpctn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.havefunace.top/Article/details/gtljkqnrfs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.meibo888.top/Article/details/gtqnykiefj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenzaomai.com/Article/details/gtrctkltmg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdmleexw.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtjqovkbmk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtzqykokcf.html

PHP:  implode(", ", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjxlvqiqz.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyvmpqzc.html

TS:   arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdohfsosn.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtsrcabnoa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtzsswrgot.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtpglguzks.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtolixjwaa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlpmpfybt.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtlstbmasx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaktblolv.html

[E01] 拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtkgqvfqiy.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xinyue.icu/Article/details/gtpyzourcm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtqqhzkmdf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtfykpicxm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sufxvd.cn/Article/details/gtjbtevypx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtyipriuqj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.pycfn.com/Article/details/gtzpfzbrqp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gtpmunnstu.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gttglxkvqm.html

[E02] 重复字符串
来源：http://dali.xuanzx.com/Article/details/gtjoqwjzdr.html

Py:   "ab" * 3
来源：http://dali.yj20258.top/Article/details/gthvacqegr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gtwzrupkau.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtpxwejixl.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gtfmrhxfem.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtneauhgzm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xuanzx.com/Article/details/gtcnrdjbbj.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtonjsvtdv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnepcqwb.html

[E03] 截取子串
来源：http://dali.gaohongyu789.top/Article/details/gtjocvhpzo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gthhpeokdb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gteivchrwj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtifihldkz.html

TS:   s.slice(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtvchbdzja.html

Java: s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtpxbnxzql.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gtttxptskj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtpvclrnfi.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtvpajqeua.html

[E04] 查找子串位置
来源：http://dali.yj202588.top/Article/details/gtjuidxjzn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gzhubu.top/Article/details/gttmdqspnp.html


<!-- 参考信息 -->