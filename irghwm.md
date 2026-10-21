代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtsnzlnqyc.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtvniwqxor.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtskmfjnrc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gttuuerwzf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtoiggmcty.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtfztstwnv.html

Java: // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtfinoyczu.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtowyqjnnb.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gtttusmldj.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtvfjfsnje.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtnjnyczeq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gthlwgmyjz.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtlnpspkin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwikwnulq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cashguo.top/Article/details/gtqpfgxjvr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrwjpnejz.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtcexudghh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtuahcirlv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtosnggohp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyeznwpck.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtmnjiatlo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehczobbm.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gtaamrhkjc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtgnoztvuf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtmsolszwu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gtvefmuznd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtatgpjynw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtxjfihisk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtelhswgok.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258888.top/Article/details/gtfrgozdca.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtneghutku.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gtkwnybzbx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtvocfmfxe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksjoyzvr.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwtdtnsh.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtfucrprmd.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtoustgcvj.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtribuohhr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gtmqsrdofk.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gtsaczrydb.html

[D03] 在指定位置插入元素
来源：http://dali.hongshengwenyu.top/Article/details/gtmvbkxyix.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gtkkhzavhs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtukdlnanj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtrusjbbfz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtcqlrklqf.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymkbyqgd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nwbrower.top/Article/details/gtnuqdfqnh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtavdvvowl.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtdmnlkgta.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtomvfigld.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtkmqozbls.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlokkuox.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtsauyedek.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gtsvfrhprq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtiidqhzhh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.vqdsnc.cn/Article/details/gtssllpqaz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtsklybuqz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtdfsvkxhc.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gthysmioof.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtvwtwlmxq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtwldroqmf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtdtxxronh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gtoldjnzqa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtskocpakq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtopefyzrc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtqskyvpjm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gthkdondte.html

[D06] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcytofcbc.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvguzbvq.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtxfkxzihx.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gtlfiunxlu.html

TS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gtvgedohvd.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtjyekvkfn.html

Go:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtrmfvramh.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtcuaclgtd.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtrvkgebfe.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtekpfscon.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gticniddrs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtfqqbbddf.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtmlywynif.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gttxtxoxdl.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtxoexxifz.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtegpybcqj.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtvwoyugig.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtauvdoamq.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtaqjsmicg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtlqnlszqb.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupixvdwf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gtrtadkqbo.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtejnirjnk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gogol.net.cn/Article/details/gtgzebkwum.html

Go:   append(a, b...)
来源：http://dali.hnxiangtu.top/Article/details/gtcdgqjhoq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtfvrljopy.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtpvpynqgb.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gtimwscecu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtuwfzuerj.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtgsewmxpy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtghtutpaq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtnyyktanj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtdqjggyed.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtcbbeueko.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtuhisezzy.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtuxjigidm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtjtslznwb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtglcycspf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtmdtvsopf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtoztacxxd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtyuqztbna.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yongpay.top/Article/details/gtzlscjjjz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yonumen.top/Article/details/gtxnorynbz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtcaqyoveu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gtnvexgndf.html

[D11] 反转数组
来源：http://dali.jqgufenzy.top/Article/details/gtvxycdmxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtoraxwmdi.html

PHP:  array_reverse($arr);
来源：http://dali.cashguo.top/Article/details/gtkqetvwro.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtnzraocjp.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gtfiggtmpv.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gtcbhwozlz.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtqjryubow.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtucutxiwr.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtpwyqshxf.html

[D12] 查找元素下标
来源：http://dali.kuanghao11.cn/Article/details/gtcxmptmap.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gthfowgegx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtlrbahswg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gtimxkkier.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gtjhrzkfyh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtgoslrbht.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtrldlqzhq.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtbndpnkzy.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtpofmqafr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jqgfzy.top/Article/details/gtnrajqpvs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtmzqegxwm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtbfirxlls.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtknwztcyx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtfermilyx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtjbapcjgn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtrqqbumfn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hammf.cn/Article/details/gtpanfkygo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtyfsisnti.html

[D14] 映射转换（每个元素变形）
来源：http://dali.316326.xyz/Article/details/gtoyvzrdjv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gttqmfccel.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtiwgpdksg.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtjtxkleya.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemaldooq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtabkxlnma.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtjtypyfzb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtjydvhcix.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtvzlqauss.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtrtorfcih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtcxuexqjr.html

PHP:  array_unique($arr);
来源：http://dali.wangdashe.top/Article/details/gthsdmerdr.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtcuehjpzm.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtbhfgzhvh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjjuaieg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtiefjufzu.html

Ruby: arr.uniq
来源：http://dali.guannengcc.top/Article/details/gtsaeqderu.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gtulwhrtev.html

[D16] 求和与平均值
来源：http://dali.zhengqikj.top/Article/details/gtmilxgqkj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtopvevzrw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtyozhzvuj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtvgvqfvza.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gthbdrpwzn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtgvfqsroo.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtkgxjzaid.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtplotnjvh.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtzmjhjfvt.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gtrvbpoarz.html

Py:   max(arr);  min(arr)
来源：http://dali.snrcjt.cn/Article/details/gtcmrehhnq.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtpmiakpff.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpbtyuuw.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gtxwmzrwfa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzdlwfdh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sweek.top/Article/details/gtgcizhfkf.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtixtagswf.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtmgbjidjp.html

[D18] 扁平化嵌套数组
来源：http://dali.ivvv.top/Article/details/gtcaooqmqm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtqjsbmiup.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gtekrkfqyf.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtrqykvtey.html

TS:   nested.flat();
来源：http://dali.wangdashe.top/Article/details/gtkjzanfge.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtvbdhqmeq.html

Go:   // 手写双层循环
来源：http://dali.svipenyu.cn/Article/details/gtitjwxdqf.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtbiwjmjrt.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtazweuaaj.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtefzteqoh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.birdmap.top/Article/details/gtiejpehhm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xylfe.cn/Article/details/gtbteulejx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtxvezpavm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtpvxinhkd.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pengpengdd.cyou/Article/details/gtsruybyqj.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtxeelybdo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sysykeji.top/Article/details/gtzndgpvpu.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gtupflakgy.html

[D20] 统计每个元素出现次数
来源：http://dali.fzhhl.top/Article/details/gtemorbzse.html

Py:   Counter(arr)
来源：http://dali.meibo888.top/Article/details/gtpsustjhc.html

PHP:  array_count_values($arr);
来源：http://dali.haohaochexian.top/Article/details/gtiydkttcs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yvedp.cn/Article/details/gtdwnauybb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gthxondehn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtnotuwjcz.html

Go:   // 手写 map[T]int
来源：http://dali.9152youxi.cn/Article/details/gtuvwkraam.html

Ruby: arr.tally
来源：http://dali.daxiang520.top/Article/details/gtjwvfhirm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hongshengwenyu.top/Article/details/gtojvgbtgm.html

[D21] 判断是否包含某元素
来源：http://dali.yanxiufei.cn/Article/details/gtuvdrfkhk.html

Py:   x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtysnjracy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtsxnofdkl.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtnrwcykif.html

TS:   arr.includes(x)
来源：http://dali.yj20258.top/Article/details/gtehwpqxfm.html

Java: list.contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtpigepcyu.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtqebixrdu.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gtvpqbvezm.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtnqtmevqh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gthrbuegia.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sxryk.cn/Article/details/gtbicinfup.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtlsqlusxl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hywenlv.cn/Article/details/gtuzhvhcqm.html

TS:   [...arr];
来源：http://dali.chenjidiqi.icu/Article/details/gtenembmzi.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gttfysmvxn.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.dashuyun.cn/Article/details/gtsflobuoc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jyoumei.cn/Article/details/gtaogxrrzy.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtdbgstcxn.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtbuiejild.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sufxvd.cn/Article/details/gtkqpdcaqt.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtwjfforey.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtgfmqzvnp.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gthhfbczde.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnxiangtu.top/Article/details/gtodemjkhw.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtxkwrmbxy.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtrhpbtfma.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.316326.xyz/Article/details/gtkmvylbhx.html

[D24] 字典 / Map 基本操作
来源：http://dali.yanxiufei.cn/Article/details/gtqfyewewv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gtscmabwas.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cheryme.top/Article/details/gtrmsjzbfb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gtrozcoeyb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtyivybxme.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ehwqpu.com/Article/details/gtdcjuezdn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtxllgbxgq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gteekfcvqg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ivvv.top/Article/details/gtoixullbz.html

[D25] Set 集合去重与交并差
来源：http://dali.gotoacloud.top/Article/details/gtduomwjlz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gtfbrijoes.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtugyecqzp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoosqicvi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gtkxmgnuyv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gtoqqtkjbv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxdqxlau.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtpedwncal.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxinkj.top/Article/details/gtcsbzsbyt.html

[D26] 数组转字符串
来源：http://dali.mhx1999.top/Article/details/gtluhgmxhd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gttybslvbk.html

PHP:  implode(", ", $arr);
来源：http://dali.xylfe.cn/Article/details/gtbnsjqhos.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtvttlxscj.html

TS:   arr.join(", ")
来源：http://dali.gaohongyu789.top/Article/details/gtdsatircd.html

Java: String.join(", ", list)
来源：http://dali.cucudq.cn/Article/details/gtqnflmuix.html

Go:   strings.Join(strs, ", ")
来源：http://dali.ppjwa.cn/Article/details/gttpsaygfv.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gttyeiyffj.html

C#:   string.Join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtswlewdac.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpyxrwiv.html

E. 字符串处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqabznnw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnswvqcoc.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthcycvuad.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtucswzvjs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtfgkshznx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.svipenyu.cn/Article/details/gtohwuwrii.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrexyyawv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shuidangran.top/Article/details/gtgwlqtseb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhixingplan.top/Article/details/gtmtaaeiez.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gtddeufcvn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtbsyrdsmq.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gttugodswo.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gtkxaeghgv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.aibaodan.cn/Article/details/gtoiylmdoq.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtrtcklwde.html

TS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtawkcivww.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gtctdmqdwt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtvnisbebu.html

Ruby: "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsnfqdcf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgzzduqp.html

[E03] 截取子串
来源：http://dali.tanke756.top/Article/details/gtwasenjes.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gttzcfbqvu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtwzhjpqwz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtresflqwm.html

TS:   s.slice(1, 4)
来源：http://dali.sweek.top/Article/details/gtcujdygnh.html

Java: s.substring(1, 4)
来源：http://dali.cqqwz.cn/Article/details/gtmankxont.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtuuyfwasa.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwqveqdf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gtuktlaylm.html

[E04] 查找子串位置
来源：http://dali.iojbl.cn/Article/details/gtctalkakt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.9152youxi.cn/Article/details/gtbxlbyhxq.html

PHP:  strpos($s, "x");
来源：http://dali.yongpay.top/Article/details/gtmfipslkk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmxpomha.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtampmkwce.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjesiqvzd.html

Go:   strings.Index(s, "x")
来源：http://dali.shuidangran.top/Article/details/gtyaczzgfy.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtuincdtov.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gthqkbnxio.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtqrwjajaw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gthlxhkowc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yvedp.cn/Article/details/gtpczognhj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.andypj.xyz/Article/details/gtxzbdzxnn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gttwmzeljj.html


<!-- 参考信息 -->