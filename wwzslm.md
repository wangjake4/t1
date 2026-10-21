代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gtwuupgwry.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtiukeqkau.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gtcdelhtrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gttgomttdh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtptdrinxl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtcwsbvlwj.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtfswqzpuq.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqzhwjsr.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gtppzghtga.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtjwvapwhv.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtsenddujq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtzkckexmp.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtascnfdxj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtnlvhgdiq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gtlofanbgj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtqyvvtgmw.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtxmjadrqb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtrgqimuku.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtkkmetyfk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybfbpubi.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtquapxsjt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrpnvwwjo.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfeacsxp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtusdgnlgc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtfevzieyy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtapmhgekk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtvvsffcok.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtwanrlzxn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sxryk.cn/Article/details/gtmatiaqlz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtmzxozetl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtdzzjznjt.html

[D02] 追加元素到末尾
来源：http://dali.yanxiufei.cn/Article/details/gtjasdrmnw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtgjdpmfnh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhengqikj.top/Article/details/gtubgnktpw.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtnszjahpd.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtznffzshi.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtilimzbbc.html

Go:   arr = append(arr, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtothzjkfm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.havefunace.top/Article/details/gtaejfqhqc.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtdbhvjrna.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gtvmujpcoo.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtbqmsajcb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtzyfkyekg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtrrxyyqjm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtiadhsszg.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtrxrwttmg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtccmulczo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gthyhvszpg.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtpxpsjyvz.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtxhzcmzga.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtvugcaclb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtahvpbhmo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtwuyhqgyi.html

TS:   arr.splice(0, 1);
来源：http://dali.haohaochexian.top/Article/details/gtngkbriaw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtxoufytze.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtmguykvye.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtfbzppjfb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.0kj1m.cn/Article/details/gtkrxalzwp.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gttgxivzkm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtuaittpgn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtrktudgej.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gttxlhlykn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtztrnvciv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtziqcqohv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtcbqohbxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtzwgopndn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtdxezheew.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtwnhlwbxx.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gtwinpbioq.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gtjasbiiqp.html

JS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtarhpvbnl.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtdoxyupvn.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmjqssom.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtvnjnhspu.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtslkvgjhe.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtbojvqvyr.html

[D07] 切片 / 取子数组
来源：http://dali.bjfxy.top/Article/details/gtdaycqgfm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtnycohjih.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtbaoqgsqw.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtgajyzoru.html

TS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtottfdqve.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtccsbrwqd.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtkntghmim.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtkzdbahgv.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtgaqoifow.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gthxfsrfcc.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gthzgxgikj.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gtyowpgrig.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gtftnefkri.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtpiiboeuv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtxlrnrcxt.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtgfdtyygc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yongpay.top/Article/details/gtcgwqmjyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtqzawzpcf.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtcirljlno.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtjqiiwuqd.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gtkcecljqk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtokdfxlvr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtbfdddhyg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtsqelvqns.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtjcyvqdvk.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtgqyuvdqy.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtpyrabocq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtddrjriap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtbwxucucb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtyhpafpwf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtyfmjlucp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.havefunace.top/Article/details/gtugugoruh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtuvdcijtl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhligajz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxinkj.top/Article/details/gtvzavgqvl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtlvcbnoix.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtprufntdt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gttrgmhehf.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtlinlsqbr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gtxsmpwjhh.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtnblqioav.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtqopzxeoi.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiphpidi.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtqznubmjk.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzavbknk.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtmsqxjbpu.html

Py:   arr.index(x);  x in arr
来源：http://dali.xziqi.cn/Article/details/gtymfoyqhy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuiatyed.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtiowoogne.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtqpespgqu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.0kj1m.cn/Article/details/gthgrozmkh.html

Go:   slices.Index(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgymfyscu.html

Ruby: arr.index(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrcwvpga.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtchtfizgm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gtnkenfnpn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yuxming.cn/Article/details/gtgpdqqqng.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtqlnygslb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtsgefndxm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtnvuidtdn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoqwedzy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtrooyfrom.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtgiewsgpg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtiscajmeh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtzhbsnoyf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtkbpnompk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtwcobwh.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtqwyywznr.html

TS:   arr.map(x => x * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtwjkhakjw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtrwbczcnk.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsszftxzo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gttyuqmirc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtavlgifrl.html

[D15] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnyluqsm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtbpxlbfpz.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtxugjaauj.html

JS:   [...new Set(arr)]
来源：http://dali.guowangkeji.top/Article/details/gtyyhognkk.html

TS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gtawjfglei.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.guowangkeji.top/Article/details/gtzmurfbwi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gtvcirbdnk.html

Ruby: arr.uniq
来源：http://dali.daria6918.cn/Article/details/gtadkxawof.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtpijuvmzj.html

[D16] 求和与平均值
来源：http://dali.yongpay.top/Article/details/gtmllsgkwf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtujfwzkge.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.havefunace.top/Article/details/gtuietujgy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gotoacloud.top/Article/details/gtkqwdvxsw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtclwxwpiu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtthmlfzym.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtynafqdfb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtcxotttzu.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtqulfxugc.html

[D17] 最大值与最小值
来源：http://dali.zhongyouzk.top/Article/details/gtylamrxkm.html

Py:   max(arr);  min(arr)
来源：http://dali.fzhhl.top/Article/details/gtuzckggjz.html

PHP:  max($arr);  min($arr);
来源：http://dali.tianlin.xyz/Article/details/gtiagtlpzz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yj202588.top/Article/details/gtyxtwlvwr.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtqhbanaxh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gthhdxwrqx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtrleznavb.html

Ruby: arr.max;  arr.min
来源：http://dali.birdmap.top/Article/details/gtpstixcim.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtqlqlntrw.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtndonmrsy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gtmcfbezoj.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtsooomndo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqxhibcl.html

TS:   nested.flat();
来源：http://dali.yuanzhike.top/Article/details/gttzbnmjhc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtlhhdlvkj.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomxxnuzj.html

Ruby: nested.flatten
来源：http://dali.jlsjyb.cn/Article/details/gtsaimnzzk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtaagnmvhk.html

[D19] 按字段分组
来源：http://dali.havefunace.top/Article/details/gtudadorob.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtgztwizxv.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tianlin.xyz/Article/details/gtfqizcsjq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.andypj.xyz/Article/details/gtkiuixoxo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtdofdnbzv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtwbmijrxs.html

Go:   // 手写 map[string][]T
来源：http://dali.jianghu66.top/Article/details/gtzpssdwnc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daxiang520.top/Article/details/gtknwwlkok.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxinkj.top/Article/details/gtshhvahmn.html

[D20] 统计每个元素出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gttfbrigwp.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gtayfkuity.html

PHP:  array_count_values($arr);
来源：http://dali.yuanzhike.top/Article/details/gtwigalwow.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hongshengwenyu.top/Article/details/gtrjkenxtj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfodxwta.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtywxhzqck.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gtsktvbqfc.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtplwcgqxr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtpvfljncu.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtjaprtnxp.html

Py:   x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gtyxvndyoo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.guowangkeji.top/Article/details/gtswqsxnjd.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtyhmobxiz.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gttfvoakxc.html

Java: list.contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtecgvgvob.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtuzrumvfn.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gtpavtjncr.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtnsrjlkew.html

[D22] 复制数组（避免共享引用）
来源：http://dali.cdnleiting.top/Article/details/gtxxxqbimd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.aizwys.cn/Article/details/gtegnwxznx.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtkqdkojcx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gtliccmnqy.html

TS:   [...arr];
来源：http://dali.birdmap.top/Article/details/gtlujpfwlq.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gtcmplovkk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hywenlv.cn/Article/details/gtqhwlogki.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtkwfvfqal.html

C#:   new List<int>(list);
来源：http://dali.haohaochexian.top/Article/details/gtjmuwimvh.html

[D23] reduce 累积计算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqhfsyzf.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtvdikcpmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yvedp.cn/Article/details/gthqejkfjk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjubqxusk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xziqi.cn/Article/details/gtmkeiugbu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.316326.xyz/Article/details/gtpuusajoj.html

Go:   // 手写循环
来源：http://dali.guowangkeji.top/Article/details/gtempcfmgt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gthpoplzjp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtsmlevmly.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gtliljtlao.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj20258888.top/Article/details/gtcbttdnyq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtnjudcsgc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtuvziltve.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtepztdyap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtkwcvjmgy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cheryme.top/Article/details/gtlgdkmyfk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tian-w.cn/Article/details/gtoxygunnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gtqchvobfe.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtchduharn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtxkqaixqc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yvedp.cn/Article/details/gtgoppzrph.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aizwys.cn/Article/details/gtiochcvmh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtnynieelx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdxzjncj.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gzhubu.top/Article/details/gtgoofciqn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtmztoptyr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtuyysaalb.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtbdnjodge.html

Py:   ", ".join(map(str, arr))
来源：http://dali.chenlongwang.top/Article/details/gtllbowrvv.html

PHP:  implode(", ", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtiqclfdcu.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtjzifqpoh.html

TS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtjtgxgtvv.html

Java: String.join(", ", list)
来源：http://dali.meibo888.top/Article/details/gtyoqcitgx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqaxhsko.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkygvsen.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtezearurq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqbabhzrv.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtcipbfsmf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtopepqgbb.html

[E01] 拼接字符串
来源：http://dali.yueranfly.top/Article/details/gthakzofkh.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtbgvdfoau.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xylfe.cn/Article/details/gtnsjgbank.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohhrsgvv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtjlaiobai.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnwfhtqb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlgqkzff.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtjwyrqntx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gtdguqjhpk.html

[E02] 重复字符串
来源：http://dali.vqdsnc.cn/Article/details/gtmphugmjn.html

Py:   "ab" * 3
来源：http://dali.wangdashe.top/Article/details/gtmsyobkrz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.havefunace.top/Article/details/gtngjbaurh.html

JS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtjkzkuucu.html

TS:   "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtaugsfpob.html

Java: "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtoxzlzjbh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtntamwvmw.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtaydwcueu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cucudq.cn/Article/details/gtgeefltqt.html

[E03] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gthrasazxs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gtvhrnoubb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtxoilrvbf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtcanuykuo.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifiqclyw.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtabgfyqoq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtgvbxswjd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenzaomai.com/Article/details/gtipyylldv.html

C#:   s.Substring(1, 3)
来源：http://dali.svipenyu.cn/Article/details/gtkzcprbln.html

[E04] 查找子串位置
来源：http://dali.hysaishi.cn/Article/details/gtoundqtfj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtiffjydmg.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtzxgdluwt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxzfcpms.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtotfhvnnk.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtsulcmfgo.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfegwxfqw.html

Ruby: s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtxkzkgbbb.html

C#:   s.IndexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtfzfxgxeh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtbzcsknhl.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.havefunace.top/Article/details/gtkzmjeopl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxdimlig.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gtxvzsqixt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gtpacxgfen.html


<!-- 参考信息 -->