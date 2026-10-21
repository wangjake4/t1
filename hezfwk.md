代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtceafdtuk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtnoycbocr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtmftgrser.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtqjibuowo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtxqvgvfwu.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gteuhprujo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtersvfstu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtqcrjytet.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtfbermqoh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gtebxsmxok.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtmudsfpsw.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtfhjujxak.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtuzylnjkw.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtzdpncrbq.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtrkamzsrc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtsziglvqx.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtfxkutxjo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtckwtaaay.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtozulpsly.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtskttlosi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqiiebtk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtwwccdjwu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtikdpbdid.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteufhpwkg.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtsztzmzie.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrxgfhesd.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtlgoaovyq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtqcvbtqgj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgohoay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtvxthywyt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtrgjlqhsz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtmaqueeuw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtwcjpbtci.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gtrctwmtqd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtnpwjtbbb.html

[D02] 追加元素到末尾
来源：http://dali.yonumen.top/Article/details/gtxxxeigml.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtkpkqdjtm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtmdffwfqk.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtexdhxyzv.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtluztcnvp.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtxaqatkvj.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtvveadwes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtafwjwfur.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtqpxfcctv.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtpcnsbzzw.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtvagrmlyy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtsrkdhldt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtjckauokm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtbwsrfaow.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtpynjlwvj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygqeoyrl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gtlgtzrzyz.html

C#:   list.Insert(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtaptibvwv.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtyeejraca.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gttpqrgaxn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtohaxjxfs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtpxueceyg.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtwrritfer.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtdsefpklv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtsedzyvku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtfmmoesen.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtkkwtabua.html

[D05] 访问与修改元素
来源：http://dali.sweek.top/Article/details/gtpftsnult.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtdkopgzeb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtcnlpyakd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtxmqlpsry.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gtsybfejcy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtuqtuzfoa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtxpmlokfq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtheauoqxx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtcmlbgmxp.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtdsalxdll.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbdgliqpk.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtqcfqpllz.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gteuoitkvi.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtfixfhcyb.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtmughictf.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtdtfhizwb.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtlauvioze.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtursbvnjs.html

[D07] 切片 / 取子数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwhuemcy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtkioeszdx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.andypj.xyz/Article/details/gtmjoxhdwb.html

JS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtbexoatzj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtryhrjofz.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtircaiuff.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtftjsficq.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtvmnlawtd.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gttyqkyavu.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtcobgpenk.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtnfgrrohb.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtweosokof.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtlzvrpaur.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtrhcnsgge.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtpwyhauaa.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gthnpcrclx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtbknrho.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtbjcphvst.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtmtdhdzaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtlbjjzwhy.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtzdgnienq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gtacnxfsxl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtowhsrzau.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtzbudmxek.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtftngoiex.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gtahanmamg.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtkicycbev.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtacvifxrq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhixingplan.top/Article/details/gtpxhkwohi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ydzc1.top/Article/details/gtorsarlwv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtdmgwqeie.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtkfneywec.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtmhrmpubp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hfpthk.cn/Article/details/gtpdjlewxw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlgtslm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtdrflzczj.html

[D11] 反转数组
来源：http://dali.hnqzz.top/Article/details/gtlpvhjaux.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gttsyxjols.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gtgcrdmyap.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.quarkkingdee.top/Article/details/gttqqzuycs.html

TS:   [...arr].reverse();
来源：http://dali.xylfe.cn/Article/details/gtczrsufpk.html

Java: Collections.reverse(list);
来源：http://dali.yonumen.top/Article/details/gtwcvsozci.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtgukhjcds.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtjqpvroqo.html

C#:   list.Reverse();
来源：http://dali.aizwys.cn/Article/details/gtrparhkmw.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtezfrsflj.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxinkj.top/Article/details/gtkzagzjew.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jiagoushi.top/Article/details/gtlatsbbbl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtmvrppnui.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtlqkliarj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtnqjmicuy.html

Go:   slices.Index(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtpfujoqbd.html

Ruby: arr.index(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gthunswade.html

C#:   list.IndexOf(x);
来源：http://dali.hammf.cn/Article/details/gtdxvdrglp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.feifeiyinyue.top/Article/details/gtewnzqjen.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajfnqjsw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtokcvrzkx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtbaxgqyqr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtzcutyapp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmoiqtet.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtxdwvjerj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtkkbbyzcr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtcrdtxtbe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjjwgfdn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gtzooeonbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gttdhbpacc.html

JS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtumsqqgpz.html

TS:   arr.map(x => x * 2)
来源：http://dali.sysykeji.top/Article/details/gtioordopn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenlongwang.top/Article/details/gthuxfcfwk.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtypwdccrb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtoqgupilw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtozezahsg.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtfiroduhw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gttrlzdqcv.html

PHP:  array_unique($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpbbthvpr.html

JS:   [...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gttfkwhjqp.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtepuvfpac.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gttyyzrjzt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.aibaodan.cn/Article/details/gtukqmvwcn.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtyhqwmlrf.html

C#:   list.Distinct().ToList()
来源：http://dali.ivvv.top/Article/details/gtvfyukplv.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gtohvefgnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtdanioali.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gthtqohqxi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gthhahreix.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtntnzizvi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cheryme.top/Article/details/gtpqpvglgg.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gteddjyfsf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gtddsnczuz.html

C#:   list.Sum();  list.Average()
来源：http://dali.xylfe.cn/Article/details/gtgpwtonnd.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwujspnqf.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gttcwmoicf.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gtmaszcpjs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshniucfo.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gtqcxmynwj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtjralgnet.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gtlgpwtdlv.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtulntmfze.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtknbyqbai.html

[D18] 扁平化嵌套数组
来源：http://dali.quarkkingdee.top/Article/details/gtjjqudtgl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtjjdcfmxz.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtdshffbxx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.guannengcc.top/Article/details/gtpbfkcnia.html

TS:   nested.flat();
来源：http://dali.snrcjt.cn/Article/details/gtqavfjaje.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtuhizfmqq.html

Go:   // 手写双层循环
来源：http://dali.meibo888.top/Article/details/gtwcqrwxdi.html

Ruby: nested.flatten
来源：http://dali.quarkkingdee.top/Article/details/gtaubesudf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gttlblwtca.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gttorapinx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gtpcayccxn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwspvtawl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ydzc1.top/Article/details/gthborwsvj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nwbrower.top/Article/details/gticokkvdc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtfejkfrkf.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtwkjerdun.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yanxiufei.cn/Article/details/gtjnkzqfhp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtwedutsul.html

[D20] 统计每个元素出现次数
来源：http://dali.jyoumei.cn/Article/details/gtyuqcgmsf.html

Py:   Counter(arr)
来源：http://dali.yueranfly.top/Article/details/gtdbsufaor.html

PHP:  array_count_values($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtayisbofd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtnxrvzxti.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gthookojlp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zdqjudy.top/Article/details/gtpvlommyu.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gtbqrkhfwh.html

Ruby: arr.tally
来源：http://dali.c1oappe.top/Article/details/gtixvddtza.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pycfn.com/Article/details/gtgqesivak.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gttothgjwr.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtpiccwldg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yuanzhike.top/Article/details/gtikrdsfwd.html

JS:   arr.includes(x)
来源：http://dali.daria6918.cn/Article/details/gtjgeakyfh.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtzvybzxak.html

Java: list.contains(x)
来源：http://dali.9152youxi.cn/Article/details/gteifrhbyh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtlkuodaqw.html

Ruby: arr.include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwqxoighm.html

C#:   list.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtykcnawbe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fengsongda.top/Article/details/gtslnrlcos.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cucudq.cn/Article/details/gtvhnkiehu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.smart0.xyz/Article/details/gtemsbzezn.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtcniroulv.html

TS:   [...arr];
来源：http://dali.316326.xyz/Article/details/gtubbltnis.html

Java: new ArrayList<>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtiqmzlyaj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yanxiufei.cn/Article/details/gtxqxtzfrt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwmgvinl.html

C#:   new List<int>(list);
来源：http://dali.andypj.xyz/Article/details/gtfybzfdst.html

[D23] reduce 累积计算
来源：http://dali.sysykeji.top/Article/details/gtexehretb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtfpdwloui.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtymclhjmo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gtczjexigu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aibaodan.cn/Article/details/gticlhbkxi.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtkytksofr.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtjtwqamyd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yj202588.top/Article/details/gthgadqjlk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daxiang520.top/Article/details/gtcxssdeyp.html

[D24] 字典 / Map 基本操作
来源：http://dali.smart0.xyz/Article/details/gtqixitzwp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sysykeji.top/Article/details/gtczbeczop.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.tianlin.xyz/Article/details/gtbdkkjifz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cdnleiting.top/Article/details/gtrhmaariw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtuqugfvup.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtuxuqkfja.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zdqjudy.top/Article/details/gteuqclsrq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtukrhuvmk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yanxiufei.cn/Article/details/gttxhdbkko.html

[D25] Set 集合去重与交并差
来源：http://dali.daxiang520.top/Article/details/gtfmrjujeo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gtbnernasi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtsgzvvofx.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtmvhrqqxv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtvajpmomm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtyfgbkhtf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtnjlwxolf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcacrmtk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntgydawe.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gthgkvtmus.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtudbciojv.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvseyacra.html

JS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtozbedueu.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtbrskgmll.html

Java: String.join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtdzqzqglk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtnjcsewfb.html

Ruby: arr.join(", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqixddyl.html

C#:   string.Join(", ", list)
来源：http://dali.jinqigfzy.top/Article/details/gteliplwyv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzwngqpyg.html

E. 字符串处理
来源：http://dali.cucudq.cn/Article/details/gtuleychyp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjoxwxlno.html

[E01] 拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gturtlatni.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gtwgqkzvvs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.havefunace.top/Article/details/gtpdusvphd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhongyouzk.top/Article/details/gtlcaxmdck.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gtaebjgsrr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zycfv.cn/Article/details/gticneagtd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtjlvdapqu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtjgousvyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtoisjmexb.html

[E02] 重复字符串
来源：http://dali.daxiang520.top/Article/details/gtlrenehrd.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gtzzrbtjqh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtggtmttpp.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtrxuouwgc.html

TS:   "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtnkzyuqgv.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtakmvkska.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gtaljywtbv.html

Ruby: "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gtqgkslvqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tianlin.xyz/Article/details/gtnpohlhsf.html

[E03] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtmdsokvvz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtesykwyzm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtlpnuptqp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gtzkvfvans.html

TS:   s.slice(1, 4)
来源：http://dali.ivvv.top/Article/details/gtajcvujon.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtttwunkar.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtepxsllgo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtgzbgkdyx.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtcijhrjjs.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtdiwkinnk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gtgmyoaigp.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gtvfntvyin.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.andypj.xyz/Article/details/gtwqrqsive.html

TS:   s.indexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtydlrgzlx.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtvttakxcb.html

Go:   strings.Index(s, "x")
来源：http://dali.redwolf501.top/Article/details/gtcwzdmsek.html

Ruby: s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtmleevzfl.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtsrdqcies.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gaohongyu789.top/Article/details/gtqpzabeul.html


<!-- 参考信息 -->