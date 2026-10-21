代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yvedp.cn/Article/details/gtsbsrnvxn.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtaxtebefl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gtycdkjtom.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gtzaehoqhn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtffoflean.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqjgsgql.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtllrpomlm.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtqktwdpim.html

Ruby: a, b = pair
来源：http://dali.9152youxi.cn/Article/details/gtgoiswomt.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvhmrzvk.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtvayionmg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmjbquee.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtgarkgfva.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtmmmpyhio.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtoxksnnco.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtoqxhbksk.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtnyuoaace.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gtduhnctst.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gthotzwbsz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtuouzmqmp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtwjsfxjyj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqpqiyyyl.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtkjurkbax.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtjitflhqp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtnajyskrn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtwbahtoox.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtcppjwiov.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefufempm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtxqgzkani.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gtvczfsztf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtddehsdwi.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gtygmzfdho.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtkrrahohh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtxdbgwuxx.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtksjfrilh.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtuzcvuhlz.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtzsyamqqz.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gtekzwvmiw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtvgxztgzu.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtpxnexbld.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtqtehlimu.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtcmdwyypz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtxhlaovbi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtqznolymb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gttajvjpav.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtytwdlgxz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtjxpxhilw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtykbbptde.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtrxicfcvs.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtpingafsm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzzraoad.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gtzhfsglut.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtthugrhkx.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gtyqejiooo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtsfntwnpc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtaojcopwx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnfkadyv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtcknsyvii.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqkjkkpg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtgdvpgjfu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtwchsecuk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtjdylzdhc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtiixpcmyf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gtmmiefaof.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtqhchygur.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlzipqiz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowjemmho.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtqmlwcsqr.html

Py:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtdelcjcss.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtjjboxnlw.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtkrlkpzru.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtfkivwuwu.html

Java: list.size();
来源：http://dali.jiagoushi.top/Article/details/gtepqkwmfo.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtcijkxyix.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtipfnnahl.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gtvmyupjab.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gtfinnkahl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtuzaahozv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gttudbubgb.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gteddmanba.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuggrzjf.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcakndosy.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtwfgopbjo.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gteqgrtuem.html

C#:   list.GetRange(1, 3);
来源：http://dali.cucudq.cn/Article/details/gtzpjmhyyg.html

[D08] 合并两个数组
来源：http://dali.meibo888.top/Article/details/gttkdzxbyr.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gthiafedot.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtuygiprcg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtqffhsizt.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtswgbkgyj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtpzpfeooi.html

Go:   append(a, b...)
来源：http://dali.yuanzhike.top/Article/details/gtehohjkce.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tanke756.top/Article/details/gtghhniblv.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftjywide.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtfnevfzgj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtixpawnym.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtppkjppfy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtoiejuoit.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtsigoigjq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtnucerhsq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gtcgaiahiv.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtsglyqxqw.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gthkcyjcgy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtgyjfmfmt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtmaqigxdn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtraajofxr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtpwvexsvi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gtplqzkjap.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtlfhkgrni.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtvnslqnng.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtfqeziisq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gttdzcczbe.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtyngzmtxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gtftkmdxxx.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtdkuuvrmb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtsrfdwgcs.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtqsxlouvm.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtjlbfwmth.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtlbkuxlqr.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxynxgxql.html

C#:   list.Reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtkwlxajom.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtsmeknvka.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtgrsuffgu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxovyzhbi.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqizorzmg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtagbsgocu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgwlbnjk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtljdpcbyd.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtobdhzfjq.html

C#:   list.IndexOf(x);
来源：http://dali.sysykeji.top/Article/details/gtsfrjzxlm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtwxnbwixj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gtjsmctiox.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtmdpndwkr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtandjqhoe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtcblnnwad.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtljhcsboq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.daria6918.cn/Article/details/gtmdhzfmxi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtwlxczckh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtyubjsrlu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtdooyeius.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.9152youxi.cn/Article/details/gtyfqkkzgy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtraiqcgqi.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtwecamedy.html

TS:   arr.map(x => x * 2)
来源：http://dali.gzhubu.top/Article/details/gtzqicnnsm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.andypj.xyz/Article/details/gtjvavwbbe.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtimfikpll.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daxiang520.top/Article/details/gtwaheztqv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.fzhhl.top/Article/details/gtkchrqysx.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtjfotuoiw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gttossrzku.html

PHP:  array_unique($arr);
来源：http://dali.ehwqpu.com/Article/details/gthrpwuabd.html

JS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtckmywgto.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtdjjruuvi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtvqxihepo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhiwuduotai.top/Article/details/gtynbfwitm.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtzpavushu.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtfuesemuo.html

[D16] 求和与平均值
来源：http://dali.chenlongwang.top/Article/details/gtpxkllsds.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gtksghrdhu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gttjzxyjxx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtzpxxenaa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtekijxoxz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gtrcnpjyny.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtdemtmwuh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xinyue.icu/Article/details/gtvkdnyzho.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gtnjbgaehb.html

[D17] 最大值与最小值
来源：http://dali.jinqigfzy.top/Article/details/gtsixcyxjk.html

Py:   max(arr);  min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtodehdmfa.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtmzfcxxau.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtsifgxymg.html

TS:   Math.max(...arr);
来源：http://dali.gaohongyu789.top/Article/details/gtvcnkpzmn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwfhypxi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvcjdrbk.html

Ruby: arr.max;  arr.min
来源：http://dali.yangfankeji.com/Article/details/gtqwsksdib.html

C#:   list.Max();  list.Min()
来源：http://dali.cashguo.top/Article/details/gttwcisozi.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtufirprkt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtzxkdzdus.html

PHP:  array_merge(...$nested);
来源：http://dali.yuxming.cn/Article/details/gthcvwriyz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtqcelstjg.html

TS:   nested.flat();
来源：http://dali.ybcxt.top/Article/details/gtncxqyefg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gtbeqfellg.html

Go:   // 手写双层循环
来源：http://dali.nanxuanxn.top/Article/details/gtihounsud.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtdrzqwcpg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.fzhhl.top/Article/details/gteqxfqiht.html

[D19] 按字段分组
来源：http://dali.pycfn.com/Article/details/gtkglfdtki.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jlsjyb.cn/Article/details/gtnlgripuw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gtbmuszgrx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtlxdquuvn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtefvytjgr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtikjmlgjz.html

Go:   // 手写 map[string][]T
来源：http://dali.hnxiangtu.top/Article/details/gtawytfkug.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtdbwffexg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gtlhmrxxmz.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmzjohug.html

Py:   Counter(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtfsaimnfi.html

PHP:  array_count_values($arr);
来源：http://dali.hammf.cn/Article/details/gttafbarcy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtihinkwxw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtvznyhwxd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtvmivpvzi.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtpmpefiiy.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtycfjggxl.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gtzdtjqist.html

[D21] 判断是否包含某元素
来源：http://dali.zycfv.cn/Article/details/gthxewcouh.html

Py:   x in arr
来源：http://dali.iojbl.cn/Article/details/gtvtxvxlwn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.mhx1999.top/Article/details/gtlxyvjhra.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtrgxqfmkb.html

TS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtyieanvvm.html

Java: list.contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtqkzaqdzr.html

Go:   slices.Contains(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtomuhwjgb.html

Ruby: arr.include?(x)
来源：http://dali.yongpay.top/Article/details/gtqlffxpwd.html

C#:   list.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtmeihqdpy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtmdjlqvkr.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.havefunace.top/Article/details/gtctajvmum.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.guannengcc.top/Article/details/gtsekxrotk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnhmrkswi.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtomlyslsn.html

Java: new ArrayList<>(list);
来源：http://dali.dianchejie.cn/Article/details/gtuhtlryin.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtxtvrertv.html

Ruby: arr.dup;  arr.clone
来源：http://dali.guowangkeji.top/Article/details/gthjqhzoem.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtjejhowvd.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtdfbwohoo.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtacjveohl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gtpidukrjo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtbhkzbgxe.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtmrirevhb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shzxlz.cn/Article/details/gtwlpmgfsm.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtiwtbagka.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gotoacloud.top/Article/details/gtovnwhvvv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtuuvycrxo.html

[D24] 字典 / Map 基本操作
来源：http://dali.ydzc1.top/Article/details/gtyvupvpjt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.meibo888.top/Article/details/gtwlqxfnjc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtkxnrzctk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gtjubsptus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtkxqwdajk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tianlin.xyz/Article/details/gtbitxdexl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.quarkkingdee.top/Article/details/gtnozirryg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.haohaochexian.top/Article/details/gthuwgglpx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcqsatql.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtgmtpzugs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gthiuqcwxh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gtrkkfomhu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gteomxaebc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zycfv.cn/Article/details/gtuqjyigxl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsjjbwcd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shangyingyoupin.top/Article/details/gtqzpmqtfd.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gtbutneydc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gtokwvdhha.html

[D26] 数组转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkyxpvaci.html

Py:   ", ".join(map(str, arr))
来源：http://dali.bjfxy.top/Article/details/gtbbrakrhc.html

PHP:  implode(", ", $arr);
来源：http://dali.yuanzhike.top/Article/details/gtwrfnyoxs.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtivvydekh.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtuvlpymye.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtfgjtloft.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtbhouiomt.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtglqlklmg.html

C#:   string.Join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gtzabhxlog.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfxeuujnu.html

E. 字符串处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcisjygm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpteappgj.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtxsfzschd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhengqikj.top/Article/details/gtiateqnia.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtncqrdgcg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gotoacloud.top/Article/details/gtstnjpkdv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtsteyzqtm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.havefunace.top/Article/details/gtvilxfsib.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yonumen.top/Article/details/gtcmrzvfcy.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gtykqpsats.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtyfmnpcoj.html

[E02] 重复字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvstdnqwa.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gttizgsrxe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.bjfxy.top/Article/details/gtzvbvwiya.html

JS:   "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtrbbvnkww.html

TS:   "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtvbvscjfc.html

Java: "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtqrmsmxdj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtddywcelh.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gthhpuqnle.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtbonkptib.html

[E03] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtkgxhfdku.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.smart0.xyz/Article/details/gtwpdyxgkm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtrkzfnmdg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhixingplan.top/Article/details/gtcirmoxfz.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtsvacataj.html

Java: s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gtwvxdxfwb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtjjgoicdt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gtztlprhzj.html

C#:   s.Substring(1, 3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpksogszj.html

[E04] 查找子串位置
来源：http://dali.haohaochexian.top/Article/details/gtifkcrrvf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtfgdtimlc.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtufweskgn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gthqilsupy.html

TS:   s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtahcvulhk.html

Java: s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gtrvcmjnxf.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtdstrlymq.html

Ruby: s.index("x")
来源：http://dali.c1oappe.top/Article/details/gtqobjluan.html

C#:   s.IndexOf("x")
来源：http://dali.bjfxy.top/Article/details/gtjutbtyol.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cucudq.cn/Article/details/gtdjwygxqe.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.wangdashe.top/Article/details/gtqwarjumq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxuanxn.top/Article/details/gthdoignjn.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtscxljzvt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatcdxttn.html


<!-- 参考信息 -->