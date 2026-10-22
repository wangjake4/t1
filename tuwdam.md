代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtawhtrgdd.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtgwpkpvzh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtgpsxfasx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtltbhslij.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtpxxbnius.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gtdaidzkjt.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtdwakyraw.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gtqozwsicz.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtogbvhcek.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtlqhbalwg.html

[C16] 函数 / 方法重载
来源：http://dali.hammf.cn/Article/details/gtsxjurtfa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gterehmikh.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtrlxqzvvw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gtzwcdrxex.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtojajhhwf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtdrguhkkj.html

Go:   // 无重载：用不同函数名
来源：http://dali.pycfn.com/Article/details/gtflhdtxjt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gtbivmywul.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtxszxlihg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwynfyooj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtzkkzqain.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaipetlzs.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtcdidonup.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtdnmeqksv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtdrajxavh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtznhyxfpb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gttroqwirg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtisszacqa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtdzwhcpqe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtzbvubfwi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtfgpjdjhu.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtkibrlrps.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtlvcxumuf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtiazycfjv.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtcdphwbhx.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtvxisrgts.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtuoisobmh.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gttdnjqpfu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtbfsmhxgt.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtlahudelx.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubipqudh.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxxtdohf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtlbosvoxn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gtlredxaad.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.redwolf501.top/Article/details/gtzplhvyqh.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtjvaoayft.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gthngntnge.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtoaplyyoi.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtlkoyojsz.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtieblxavn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtxaovsipg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtkfdhictd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtopalzdyl.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtogatcsbd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtlxyeqnme.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtnqotynbl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtquiuvjsx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gtprdevrij.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtelfcllyy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtbfitjcwt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gtujfgiksr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtlxvmgfat.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtgxyqdujh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtuzvcczmr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtmdclvczp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrstexqrn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gttngdndml.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtqxvzevuk.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtgnwsxicj.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gtlmvfusls.html

JS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtbootzyng.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtjqqedehz.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtdxlgrzfy.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtxqnsdrji.html

Ruby: arr.length; arr.size
来源：http://dali.wangshuangyany.cn/Article/details/gtgitbtkps.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtlwelmzge.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gtwydiqgwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtafmdypqi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtltxkmzml.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtlynpslne.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtmgthkjnd.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtbqudbgsw.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtylzrtrvl.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtchrkusaw.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtgyrsggqh.html

[D08] 合并两个数组
来源：http://dali.sxryk.cn/Article/details/gtvpgtuttz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtypdqkmzy.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gtrkjdyhsn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.quarkkingdee.top/Article/details/gtnxnsjtwx.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxysxqxi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtvygvjhnf.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gthvxhxsxx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjccgtgj.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtebvhndux.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtpjkqzmqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gtuwrurcaf.html

PHP:  sort($arr);
来源：http://dali.dashuyun.cn/Article/details/gtobhlzqbm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yueranfly.top/Article/details/gtllsuwaop.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxubyzuzc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtqnldcigj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtquiqmilo.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtxcszxerb.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtmhzzfgcn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtsckgczig.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtrwrcejaf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtnpexpoay.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtewedphaj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtwddvcqny.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvlmdgkg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtlmlqfkio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtleylrmhp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gteyjopslw.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptjlbaji.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gtmyygfarw.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtngwigxot.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtkthxkvrh.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtvkrngbms.html

Java: Collections.reverse(list);
来源：http://dali.mhx1999.top/Article/details/gtpalgmmox.html

Go:   slices.Reverse(arr)
来源：http://dali.yvedp.cn/Article/details/gtksmztsta.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtnxgsphvg.html

C#:   list.Reverse();
来源：http://dali.gotoacloud.top/Article/details/gtsiroabcm.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtifkcdipt.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtlpmzwwsx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtnnegascw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gtxtwzjofy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtiztjnlhp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtjnnlwpog.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtoqeoqhel.html

Ruby: arr.index(x)
来源：http://dali.hnxiangtu.top/Article/details/gtbvmcynfk.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztjejyoy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hywenlv.cn/Article/details/gtxbnydoud.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtigkvnere.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ybcxt.top/Article/details/gtyfszzclk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtncpddybr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtpikgrqbm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gttymrxwfa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtbhjfnunc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jyoumei.cn/Article/details/gtkdhznzhk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtvtnmwtov.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtzekvgkbd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hfpthk.cn/Article/details/gtmtddtgxd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtmbeyzyzm.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtvzpiceqw.html

TS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuidunbqv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shzxlz.cn/Article/details/gtqbtkgthp.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtwcexputo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtplwneydw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtiuibbsyy.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtagadworo.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtsvextaus.html

PHP:  array_unique($arr);
来源：http://dali.gzhubu.top/Article/details/gtcbfezobn.html

JS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxxvrwwj.html

TS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtnirbtjse.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtztxnihpk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtzvnzvxxg.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gtmnsavstl.html

C#:   list.Distinct().ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtgaoggsti.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtjknibeor.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtpgyttaql.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttnvfwiqr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtofzwkzqj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtfattwkoi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtzuhdlqub.html

Go:   // 手写循环累加
来源：http://dali.zhongyouzk.top/Article/details/gtnfwyhiod.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtbfzycrno.html

C#:   list.Sum();  list.Average()
来源：http://dali.aibaodan.cn/Article/details/gtzyrgknxw.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtzvvkqbpt.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtuegwmxat.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuanzx.com/Article/details/gtlfviylta.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtkrqrrzck.html

TS:   Math.max(...arr);
来源：http://dali.birdmap.top/Article/details/gttwhpwrtm.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gteqyrjkdo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gzhubu.top/Article/details/gtdhclpqfb.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtezwezblb.html

C#:   list.Max();  list.Min()
来源：http://dali.guowangkeji.top/Article/details/gtcpfigcwv.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtbtcjvyix.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gtaretpoqn.html

PHP:  array_merge(...$nested);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoiljrao.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtsibugylh.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gteownstxz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shuidangran.top/Article/details/gtkrukpujh.html

Go:   // 手写双层循环
来源：http://dali.guannengcc.top/Article/details/gtheghqeqa.html

Ruby: nested.flatten
来源：http://dali.cashguo.top/Article/details/gtetdgdrpy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtrkiyjfcg.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gttqvecpee.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gzhubu.top/Article/details/gtzpvpwphs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtqkxnlaic.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtoyckrfkm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtogmtlxjf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gtddvvdasz.html

Go:   // 手写 map[string][]T
来源：http://dali.shuidangran.top/Article/details/gtesaperet.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.mhx1999.top/Article/details/gtybeauseb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtldhncyqv.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gtawqopjle.html

Py:   Counter(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxejsiebl.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gtggegkfac.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jiagoushi.top/Article/details/gtpyblgjzc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtbnxeffao.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pycfn.com/Article/details/gtojfsqwao.html

Go:   // 手写 map[T]int
来源：http://dali.jqgfzy.top/Article/details/gtydilfnxv.html

Ruby: arr.tally
来源：http://dali.zhixingplan.top/Article/details/gtjqfnufnu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gthntifhya.html

[D21] 判断是否包含某元素
来源：http://dali.wangshuangyany.cn/Article/details/gtccyoexus.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtgxkheyva.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtrbkinxar.html

JS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgywkpoew.html

TS:   arr.includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtcnedouuh.html

Java: list.contains(x)
来源：http://dali.daria6918.cn/Article/details/gturdbeszn.html

Go:   slices.Contains(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtlafbcqbk.html

Ruby: arr.include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtbumhrwis.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtqvcpisqa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.gaohongyu789.top/Article/details/gtujjohmef.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtxbhoywuj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtzlviwlbf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cqqwz.cn/Article/details/gthqfmjeji.html

TS:   [...arr];
来源：http://dali.kuanghao11.cn/Article/details/gtnqbvfyxs.html

Java: new ArrayList<>(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtyewnfqgu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gtmkqdjfga.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrahfgnyd.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gtknvwohak.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gtabmlcrhp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nwbrower.top/Article/details/gtzrcoqsuq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj20258.top/Article/details/gtmnyaproa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.c1oappe.top/Article/details/gtaggyzxjw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtfkfotuqm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunkrtyan.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtknsjjspn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yueranfly.top/Article/details/gtuwcclznq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gtwpadbjaw.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtwyooyjai.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtqijzglhs.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtmxirzswr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.snrcjt.cn/Article/details/gtkcyltilg.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtgoczzctt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jyoumei.cn/Article/details/gtfqfqktce.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtjyduzmxb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtphdlgqih.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.iojbl.cn/Article/details/gtktaljbak.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtqjbtqhme.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.pengpengdd.cyou/Article/details/gtsxcvekhz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yonumen.top/Article/details/gtzrkzbkah.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pycfn.com/Article/details/gtutbyubou.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.cucudq.cn/Article/details/gtmpdvhnjj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jiagoushi.top/Article/details/gtifydfgsa.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtfmqdfmxg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj20258.top/Article/details/gtkvnzbmbj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtczhbdbyz.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtcirrqssz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzswmxpwy.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gthaqozwlk.html

JS:   arr.join(", ")
来源：http://dali.sufxvd.cn/Article/details/gtrmequcie.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtvpuhcjww.html

Java: String.join(", ", list)
来源：http://dali.daxiang520.top/Article/details/gtqsiohnff.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gtsqptqegp.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwgdfwayr.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtgotqulqw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgsouxcae.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gtnkyhzjpt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthesrltao.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtzerzgrdv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gtjbropelm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnxiangtu.top/Article/details/gtipstpmqc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtxylshzmp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtfbmxydpe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gtjcddycdl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirgifmou.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtdkpupyjx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtvdyluthc.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gthwhsqbjp.html

Py:   "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtxxrixjoz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtfypdhjkv.html

JS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtixjgvaym.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtvosxsiut.html

Java: "ab".repeat(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfaocmqo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xylfe.cn/Article/details/gtzkojdnrp.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtkvodybpn.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtjmunakmr.html

[E03] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtjxnxougt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.vqdsnc.cn/Article/details/gtglrbwuor.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gthnkkngfj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj202588.top/Article/details/gtfwzsfmvz.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gthoebrvie.html

Java: s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtkgjryuqg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yvedp.cn/Article/details/gtwaiendat.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.vqdsnc.cn/Article/details/gtivqzyiai.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtfwapgmul.html

[E04] 查找子串位置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjzguwzs.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gotoacloud.top/Article/details/gtjvtdrfaj.html

PHP:  strpos($s, "x");
来源：http://dali.316326.xyz/Article/details/gtusmrvpqj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgfzy.top/Article/details/gtjkctjnhn.html

TS:   s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtzcarzmor.html

Java: s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtrkduhivt.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gttfdoidry.html

Ruby: s.index("x")
来源：http://dali.xinyue.icu/Article/details/gtyqwjwxjv.html

C#:   s.IndexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtnxmibycs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258.top/Article/details/gtsmzrdusj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtivozzaws.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yanxiufei.cn/Article/details/gtwofujmgz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtutucubrv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sysykeji.top/Article/details/gtfnsteqzu.html


<!-- 参考信息 -->