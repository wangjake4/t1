代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gttohkyscv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbpbuouzu.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckufzzqx.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtumcujjce.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtbrwyaqvk.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtpsmxacnd.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtjlptjlin.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtvxeqfmrh.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtlecamyrg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hywenlv.cn/Article/details/gtvpqperjk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtdboqucls.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtqnzmevag.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gtxnlumxzs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gtuvdugmyc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gtylceyfsk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdsoocdnl.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gtblfxqepw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtswaismzc.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtvhecocof.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtiechmmcl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtkcfjpknp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtqjlywvbv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvfquwgz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtyvfwzcik.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtspsdohuk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gturmyownl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gteqlgdelz.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtnnzmsnyp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gteuiiwtpr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtcurduoal.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtdlvoawzd.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtlhhiiaqd.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtacfepsor.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtynzceqbr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtfujhnpqj.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtlncwjkmc.html

[D03] 在指定位置插入元素
来源：http://dali.yongpay.top/Article/details/gtdmakeehp.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtotklebks.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtkqxijqob.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtlghubnwc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtwbcwuklq.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtuomzdkpu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtmnfacouh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtdhhbbnty.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtwrezrlib.html

[D04] 删除元素
来源：http://dali.aibaodan.cn/Article/details/gtiidjdkym.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtijqceeik.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtzunzjutl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gtzooeqfdm.html

TS:   arr.splice(0, 1);
来源：http://dali.sufxvd.cn/Article/details/gtpeyugsgo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gtombcejdf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtmwhxjuer.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtfkaithem.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtfppakvce.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtmwtnjten.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwsqyyyl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gttzqkvwah.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtudxhudgp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtluomljmp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gttwaejcdf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtdsbwepqw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtrmnyvsgp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtwljnpokt.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtsjzyyslo.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gteolbfsty.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtmsgouehp.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtknsxyjuk.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtllffzqrh.html

Java: list.size();
来源：http://dali.gaohongyu789.top/Article/details/gtxbamnpqv.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtngdjpnvk.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtcwgibvwp.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtblqdcway.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtugwlzsvn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtnocpxtzw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfryrtkrl.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtmxsqcjgw.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtlwvaqscg.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsejwbvq.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtdsfcgufa.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtukmvubkz.html

C#:   list.GetRange(1, 3);
来源：http://dali.redwolf501.top/Article/details/gtpdfvttbh.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtrcklqlqm.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtrydlqzpp.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gtvoqftkru.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtuenabiyw.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtwsuwxlcd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ppjwa.cn/Article/details/gtriqdaueg.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtcljafhch.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtjxdqtpfw.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtsargolbk.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtampinvsm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtdmjxmvqj.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtuaousciq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gtxqvtnxty.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gtodiccjkn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gtmmumgmrx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtqyppmdnx.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtzofnnotw.html

C#:   list.Sort();
来源：http://dali.jyoumei.cn/Article/details/gtcwcjfaxl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gtcrxtomdb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hammf.cn/Article/details/gtvmlgjqzg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtpwnqcfec.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqjsugvw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtvpttwnjo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gogol.net.cn/Article/details/gtnseapqng.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtnxqzgozu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtkmtlrrys.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtaihquahe.html

[D11] 反转数组
来源：http://dali.ydzc1.top/Article/details/gtcibrdkzp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.316326.xyz/Article/details/gtqwmimspj.html

PHP:  array_reverse($arr);
来源：http://dali.svipenyu.cn/Article/details/gtzbbvkhgp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtuyejejfh.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtqlvvuxou.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtjcqqrcrc.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtavuxrbgg.html

Ruby: arr.reverse
来源：http://dali.andypj.xyz/Article/details/gtfrkxauss.html

C#:   list.Reverse();
来源：http://dali.chenlongwang.top/Article/details/gtktmulwau.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gtmsqluglf.html

Py:   arr.index(x);  x in arr
来源：http://dali.jiagoushi.top/Article/details/gtndjgscyo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwojhqizk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtztmmqjwk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gttahcncft.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtcgbuukup.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gttivawmmu.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gtzaekivdy.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsgnkpjx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtitlbukdh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ppjwa.cn/Article/details/gtwievytmd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.meibo888.top/Article/details/gteerxsrco.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmturieo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zycfv.cn/Article/details/gtsjzhmsza.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yangfankeji.com/Article/details/gtrdssmrjd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtpkrbzswy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dashuyun.cn/Article/details/gtutnzlukm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xziqi.cn/Article/details/gtdxtbrbjx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.pycfn.com/Article/details/gtkwehkmou.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gteqkjlgvz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtdfersyaq.html

JS:   arr.map(x => x * 2)
来源：http://dali.9152youxi.cn/Article/details/gtfpsqfhrb.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtsacymilt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtljltuxbk.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gtfsnqmpcb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykdwzaee.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gtoonnreca.html

[D15] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtfnymqycd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtbjizdkib.html

PHP:  array_unique($arr);
来源：http://dali.chenlongwang.top/Article/details/gtamcatgiu.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtvelsdcst.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtocvayzcy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtcxotpmca.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtzwuafpkp.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtonkjunfz.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtfjolyjdk.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gtltxjeoti.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yueranfly.top/Article/details/gtoqqznyyi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gtmcwzfhph.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtbanoiuba.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gthnisjfpr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnxiangtu.top/Article/details/gtibbhggqo.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtzghrvmzv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hammf.cn/Article/details/gtlyihvklt.html

C#:   list.Sum();  list.Average()
来源：http://dali.shzxlz.cn/Article/details/gtkxbdngbe.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtjnhzdnsv.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtimdddrzm.html

PHP:  max($arr);  min($arr);
来源：http://dali.daxiang520.top/Article/details/gtgueyfwgu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtlaeyfwcc.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxawwhlud.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtlnkdpskt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrmnpsua.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gtjtbvkoid.html

C#:   list.Max();  list.Min()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhnmwfhx.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtvhbxmhjx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gtzujisrul.html

PHP:  array_merge(...$nested);
来源：http://dali.zhongyouzk.top/Article/details/gtpfonenpz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hysaishi.cn/Article/details/gtpxkogbps.html

TS:   nested.flat();
来源：http://dali.chenlongwang.top/Article/details/gtmvvugwmz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtvmbzxemu.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtpfchxwpr.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtgonwisul.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sysykeji.top/Article/details/gtnijxcabc.html

[D19] 按字段分组
来源：http://dali.dianchejie.cn/Article/details/gtvxnpooan.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gttjljzzun.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.haohaochexian.top/Article/details/gtccflqimg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtunvzktby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbaaqqqi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenlongwang.top/Article/details/gttdpbsfxz.html

Go:   // 手写 map[string][]T
来源：http://dali.daria6918.cn/Article/details/gtdvdkonlw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gtdkbzkflg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nwbrower.top/Article/details/gtmvfdnfna.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigfzy.top/Article/details/gtrpujenuv.html

Py:   Counter(arr)
来源：http://dali.hammf.cn/Article/details/gtlyxvuskc.html

PHP:  array_count_values($arr);
来源：http://dali.yonumen.top/Article/details/gtemthgqrp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtsrohdlji.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangshuangyany.cn/Article/details/gtrqdozrzz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtytvxnonj.html

Go:   // 手写 map[T]int
来源：http://dali.aizwys.cn/Article/details/gtevjopqhq.html

Ruby: arr.tally
来源：http://dali.hnxiangtu.top/Article/details/gtqzvnzbmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gtffcbxoqc.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtwbybrkju.html

Py:   x in arr
来源：http://dali.gzhubu.top/Article/details/gtusmdjsrl.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtozveorju.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtpmexiinf.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtfdikcktv.html

Java: list.contains(x)
来源：http://dali.daxiang520.top/Article/details/gtqgnhpdxl.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilsigiyq.html

Ruby: arr.include?(x)
来源：http://dali.iojbl.cn/Article/details/gtpjgsqkxg.html

C#:   list.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfofkvhnv.html

[D22] 复制数组（避免共享引用）
来源：http://dali.feifeiyinyue.top/Article/details/gtotgqglgu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.andypj.xyz/Article/details/gtowtnhavo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xziqi.cn/Article/details/gtlkvzlqkx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gtsfgipraw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gtqnuhikvi.html

Java: new ArrayList<>(list);
来源：http://dali.hywenlv.cn/Article/details/gtylgtvkpu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gtksizzsqk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.nanxinkj.top/Article/details/gtzmxjwnje.html

C#:   new List<int>(list);
来源：http://dali.chenlongwang.top/Article/details/gtcbifjcie.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtkdjmzxow.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtvimcmkzn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gtgaataoit.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqvkclykn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtxbnzkoiu.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ehwqpu.com/Article/details/gtfvecrzgt.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdmoqkpz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtljmabkxh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhengqikj.top/Article/details/gtwpvkgdbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gtbxpaoydb.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.dashuyun.cn/Article/details/gtaqbonaqs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gtqxvqvngk.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gthpzvywld.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtvhccgxyu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gtpfneyezq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yanxiufei.cn/Article/details/gtkechyhhk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.wangdashe.top/Article/details/gtocejuniz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jinqigfzy.top/Article/details/gtqiqqdmfb.html

[D25] Set 集合去重与交并差
来源：http://dali.cdnleiting.top/Article/details/gtuyyyeegz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.redwolf501.top/Article/details/gtumyhwkpt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtrlfkhzmw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtbvkfqbom.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtjapyvugy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtoopqsuxf.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtzyromzws.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xylfe.cn/Article/details/gtxcflzqyt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xinyue.icu/Article/details/gtjrucnppp.html

[D26] 数组转字符串
来源：http://dali.wangdashe.top/Article/details/gttmsfsebu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtrsjtxwiy.html

PHP:  implode(", ", $arr);
来源：http://dali.gzhubu.top/Article/details/gtslqkbeid.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gttmrnctqc.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtsfwbvloz.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtjyzafssa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ehwqpu.com/Article/details/gtjtnhygfz.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gtttatoizf.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gttjslvmqy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthmxrdofs.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtujssjxpg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtirziwxip.html

[E01] 拼接字符串
来源：http://dali.xuanzx.com/Article/details/gttwlyqweo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.fzhhl.top/Article/details/gtthvigykz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yvedp.cn/Article/details/gtxmlndems.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pycfn.com/Article/details/gtjixvvszh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtzyetbspg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.316326.xyz/Article/details/gttjgenxaj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gtyfcieowo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuetiantiany.cn/Article/details/gtxwxjthsn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sysykeji.top/Article/details/gthlatdajj.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtnyuqucvh.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtzduyyoef.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolcpciue.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtikfjycfr.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtkexaatbb.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtlmpteeki.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gtmadbawyy.html

Ruby: "ab" * 3
来源：http://dali.ydzc1.top/Article/details/gtncdmqizb.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.dashuyun.cn/Article/details/gtraddckxm.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdiohdum.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gthjdjkvid.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtayxetada.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtkbadzkar.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtbsdbtyor.html

Java: s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtttojmkxt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtoaqdvpeo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqxucfuh.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtxunydeam.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gtcxxbzioi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtufradptm.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gtlemngtaj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.0kj1m.cn/Article/details/gthxxbnalt.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtvdqipozh.html

Java: s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gthlavbwwk.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtfmvzrztc.html

Ruby: s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtyezkyltw.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtodugabcy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtrllwdfat.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gogol.net.cn/Article/details/gtuznjkfer.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuetiantiany.cn/Article/details/gtpjxmxhvt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtffsqgmgi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.shzxlz.cn/Article/details/gtfugeewqp.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtdikxtnau.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yj20258888.top/Article/details/gtkxrupffm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.9152youxi.cn/Article/details/gtttotluaz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtkvhrpwcw.html


<!-- 参考信息 -->