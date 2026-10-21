代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtttslbano.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtxsthiuxj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtgeemqxdi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtuhlibpra.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtlndyoqek.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtunfapvac.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtdrqroyyt.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtkqtiwxgq.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtknfkpxhi.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtmjikusvn.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtxqjecmfk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldqxxkoj.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtvnfhfimt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtxzhspnjs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtndjfxshd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtlvqxqrjk.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gtkcnpfrdi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxinkj.top/Article/details/gtlqgxruwy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpblgbxu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyqsmcpqq.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gtocyldswk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvsumyurk.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtcswdbngm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gtwvdkkptt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtgiawqgom.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gthjoajihv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtqajqwtqe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtmmugjwxq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeuxkeii.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtnrnrjyln.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtwbxbexcb.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrgylzhi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtnfqjscco.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyrludap.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtjawzkvto.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gttqhosfex.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtksyhrytx.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtskyvvhgh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gtqlcwqfwf.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtvpodxlwy.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtqupxwhru.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gthbegaptm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtrusfokls.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxuanxn.top/Article/details/gtuxkmmcpq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtuopgrwvq.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gthotqehgf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtzeaomtvr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtbsdyedko.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gtxnazksfe.html

[D04] 删除元素
来源：http://dali.jyoumei.cn/Article/details/gtxpygaxhh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gtwstnxylc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtmmyxzwrr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtvdlfxtfp.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtevbdmmqo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sufxvd.cn/Article/details/gtqdojpscu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtztvzjpux.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gttctyrrfp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nanxinkj.top/Article/details/gtklgcoofc.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtaszxadzz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtocjvsksf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtilfbfbxo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtmadzwcgf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtzghgpahn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtilbalqpa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gteyddxeet.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gthayuexnj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtnphjdmne.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtjxfjfpye.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtajezyubp.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtbhygkojn.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtdedvapjf.html

TS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gtckiufhpd.html

Java: list.size();
来源：http://dali.zycfv.cn/Article/details/gtckqzkrjt.html

Go:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gtaepgvwwx.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtvucpwwlx.html

C#:   list.Count;
来源：http://dali.yuanzhike.top/Article/details/gtajvyknod.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtbjxizuxl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gtujnrbzqr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtfirmdpli.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtelwqjwjv.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtgiymcted.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtfbogcini.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtwjlkavbv.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtqyuxasuo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtrcbgxykt.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtuxdgbgsw.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gtthqkhoka.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtlemqadhj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtqgrlgbmr.html

TS:   [...a, ...b];
来源：http://dali.gogol.net.cn/Article/details/gtrtdxwhdi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtlomphjav.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtxlkxgezv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtvrczsqlc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtjyafxrir.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gtamrsfusd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtynrhvcef.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gthtchvxbw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtkptagxtm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gtoofzmxrm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258888.top/Article/details/gtzjvlumzk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtrmeiixvf.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtrmwzzahx.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtzrwbklhb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtinbfehci.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtmtcxgilb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtmmcocdaj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtskibqpaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gthayvbdmr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtndvqowrm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gtelhyymkt.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtqnztusnl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shzxlz.cn/Article/details/gtalihwvmn.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtctowtqrv.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gttzkbkvdy.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtrncmakeb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtmmgspbwm.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtljokvvjf.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtozjpoplv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvlmouihl.html

Ruby: arr.reverse
来源：http://dali.hysaishi.cn/Article/details/gtyyzmqmyx.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gtbttgdluf.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtibyfcquj.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtcesntolx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdcheakg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtdudrstcl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfvxqmkz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gtdshjvqfh.html

Go:   slices.Index(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtjeiaymse.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gtkgdzmhyw.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtzksnlgla.html

[D13] 过滤（保留满足条件的）
来源：http://dali.316326.xyz/Article/details/gtdnrdeycf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjspcdvz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gtmtggjdzq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtpbxlrmqs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gtcieidfza.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtytojphih.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gthrdbvrag.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtfvhlnfol.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtlpfplzwz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnxiangtu.top/Article/details/gttuirnrib.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuanzhike.top/Article/details/gtujcqwxgn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtxytfbeqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtjrjfulpw.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtxmxoxxiv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtzyfwthxc.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtlhjrmzrp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhnaqkcc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shuidangran.top/Article/details/gtyjbdszts.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjswlnkhy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtkpmwraed.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtmhlfctjz.html

JS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtbppdyffr.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtzpiutcgl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtkdgcotss.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hfpthk.cn/Article/details/gthwtnsjsk.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gthybsnxyi.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gtmetbvhtz.html

[D16] 求和与平均值
来源：http://dali.haohaochexian.top/Article/details/gtizhfgugg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj202588.top/Article/details/gtpcwatadw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xziqi.cn/Article/details/gtxwlwrorc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gtdxwhndqj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttebogmvd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.daxiang520.top/Article/details/gthqvdmmss.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtjecvlmxk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtbxizwkjw.html

C#:   list.Sum();  list.Average()
来源：http://dali.guowangkeji.top/Article/details/gthdrhnfli.html

[D17] 最大值与最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidirtztk.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmozkqwve.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gtwitpmvux.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtejhmcxdo.html

TS:   Math.max(...arr);
来源：http://dali.c1oappe.top/Article/details/gtsytiexqz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.svipenyu.cn/Article/details/gtywmleaph.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmdckobtu.html

Ruby: arr.max;  arr.min
来源：http://dali.guowangkeji.top/Article/details/gtuzonfgrn.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gteoigxxid.html

[D18] 扁平化嵌套数组
来源：http://dali.feifeiyinyue.top/Article/details/gtjfmotvaq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.iojbl.cn/Article/details/gtqpfpnoef.html

PHP:  array_merge(...$nested);
来源：http://dali.0kj1m.cn/Article/details/gttzxycica.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtsizutwhu.html

TS:   nested.flat();
来源：http://dali.aibaodan.cn/Article/details/gtsjyophsb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtjoicppyb.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtubkxmzoj.html

Ruby: nested.flatten
来源：http://dali.xuanzx.com/Article/details/gtohpqqrib.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtprfwuxdw.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtbrvufqes.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtqmconcjp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aizwys.cn/Article/details/gtgmiiokcy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtjsdsfzni.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtxdjipprm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtanatjziv.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtoddzdtxl.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.snrcjt.cn/Article/details/gtlpwgkrvy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cashguo.top/Article/details/gtqynccwfu.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gtzsricdnp.html

Py:   Counter(arr)
来源：http://dali.jinqigufen.top/Article/details/gtbndnkgcf.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtvgxffquk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtpixjbkhu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtpdrgmfjm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cqqwz.cn/Article/details/gtrgtgxmvi.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gtozagmgmc.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtrdobozss.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtbfyxbcpl.html

[D21] 判断是否包含某元素
来源：http://dali.guowangkeji.top/Article/details/gttegacghu.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gthaqrzlkz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgufenzy.top/Article/details/gtbqeirpjr.html

JS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtnfegcwpb.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtnetdwmgv.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtvtlsrdyz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258.top/Article/details/gtlddzoual.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnrlfjxw.html

C#:   list.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtjsapxpdy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.fzhhl.top/Article/details/gtszbqinop.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfrskedjr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yuxming.cn/Article/details/gtarxssmrm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtlsqvigxr.html

TS:   [...arr];
来源：http://dali.yuxming.cn/Article/details/gtoouxiqqk.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtqlsyokta.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuanzhike.top/Article/details/gtcnuaragc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtjtlyikcj.html

C#:   new List<int>(list);
来源：http://dali.tianlin.xyz/Article/details/gtwkzvipyo.html

[D23] reduce 累积计算
来源：http://dali.xuanzx.com/Article/details/gtvkcqkpxk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtolplufas.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtpxcgwhml.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtcqpfoywn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sxryk.cn/Article/details/gthzadnegg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenlongwang.top/Article/details/gtfbygtoft.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtqjktecpg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ivvv.top/Article/details/gtjeomwjxl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gtqgpmxcyc.html

[D24] 字典 / Map 基本操作
来源：http://dali.xuanzx.com/Article/details/gtsmckvpzp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtyncnzyat.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtctvzkonn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtdhryiwub.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwtyrenf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgfxbfp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvjwlbct.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gtrisqddsx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.smart0.xyz/Article/details/gtgqqykunm.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtthxglmey.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtqcvxndhw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tanke756.top/Article/details/gtiytzyaif.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hywenlv.cn/Article/details/gtojxtajxl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cheryme.top/Article/details/gtjeyjqhdc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtvdlcgahs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gtvmlnmamc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gttbrcigmo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujjcpuzq.html

[D26] 数组转字符串
来源：http://dali.shzxlz.cn/Article/details/gtrrarbnyx.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gtuttxdyta.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtrebritdm.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtovwvvwrt.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtdmffxxwn.html

Java: String.join(", ", list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorfyxgpk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.redwolf501.top/Article/details/gtpstjaici.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtqqkzauum.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtsiqzpjkr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthdzcdzgs.html

E. 字符串处理
来源：http://dali.hywenlv.cn/Article/details/gtvvspysjm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbzwwijyb.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtkrroqqep.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jqgfzy.top/Article/details/gtfnfydgwn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtzagleeqp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.havefunace.top/Article/details/gtbuvtxvli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gzhubu.top/Article/details/gtlbrvkgqo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhipuxky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gttjzhpjor.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xuanzx.com/Article/details/gthlksrllp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gthlphlykd.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gtggjvbzau.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtygexwgsi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtudblgyqp.html

JS:   "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtmlpqxhwc.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtlxbfkiqc.html

Java: "ab".repeat(3)
来源：http://dali.yj20258888.top/Article/details/gtqqgqnjbm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtdakrsnec.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gttxxffawn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtspbuhtvv.html

[E03] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtspdlqstc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hammf.cn/Article/details/gtrhagkizl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlohpjwgv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtewrsfzdx.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtwddmruff.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gtgpeqqoth.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.aizwys.cn/Article/details/gtejddqccd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtisjxsbqu.html

C#:   s.Substring(1, 3)
来源：http://dali.dashuyun.cn/Article/details/gtusbixkzp.html

[E04] 查找子串位置
来源：http://dali.daxiang520.top/Article/details/gtwjybqqew.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtkgdgfleo.html

PHP:  strpos($s, "x");
来源：http://dali.jinghuilouyu.cn/Article/details/gtffsavzuc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.316326.xyz/Article/details/gtyhrrokfi.html

TS:   s.indexOf("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawfppcxx.html

Java: s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtadgsitns.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtcqsstjqk.html

Ruby: s.index("x")
来源：http://dali.yueranfly.top/Article/details/gtlwxtxruf.html

C#:   s.IndexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtjcfyogve.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.0kj1m.cn/Article/details/gtqhkjtuel.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gzhubu.top/Article/details/gtyixyftsd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nwbrower.top/Article/details/gtbsrwflxg.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gtdbmzqdqn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gtyfubasos.html


<!-- 参考信息 -->