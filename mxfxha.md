代发 wailian999

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xojuibte.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpmuvyb.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvyltcb.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2elkxbaei.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phavbnvi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtipov.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iycxbfdr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2heosdeqc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2uenxshzy.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjbyoox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxamrcn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsaqhqp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yubabhvo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkdeaqa.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfywohx.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwkqghk.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2quigoofc.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxrpsq.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfahtnxt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfgrmgc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qadfyywl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpliucj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ztowihby.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkglndjw.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2hojpiilm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihevhqjg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzqdwbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuzeibq.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcnbvuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeknotq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhdixnz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjexyz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2waivwigx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jrispdsq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2fyquhdnk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sltcvxgp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2krgnjbek.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsgrqau.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpuzvm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxuxqul.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2rybxoyji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nobbyvdw.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmyzwut.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kknysism.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiczqru.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgksfkop.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzcijbj.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptkkyf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnnjjcz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrtwtpk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2utofskyj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdygufe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdqenxt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvmjfcg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2eotbtmmy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2elvgbwny.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2efubfuyi.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hiofffpw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlshsta.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvahpkkg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxindwt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyorpjvi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwzgpvz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbvkjxv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkvjjvx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvtqxs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tntnhmlx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cplukdwf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2elcivoay.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mftcrshv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khtxtcol.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtomkfg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyxdeun.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwzqnlz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmguamxs.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyceorc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrgxlex.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyffxzrf.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eerccngn.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbukzgep.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcvcnqa.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbseiag.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2thywktbx.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bucwdjgg.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiapixu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbvqbzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqhgedv.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvbdoyi.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwpexyc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbhglzz.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2oaygygbn.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrkuliw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdstddb.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqzajhu.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbsxqhb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2njdomvuf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2exdtjnxh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwrvkms.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2juasgbeb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmayyuf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbvcyup.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2guxawgur.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbwnion.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsjioth.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfyoeku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdnxsnz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnplimm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2tibvuihn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjboucrc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hapjhqda.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbupcagw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfllrwha.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgcsgox.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjrrqsl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdbkpgq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2brvilody.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wdugxdoi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrggdham.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfosujtv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2jwttjjni.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2piphqgbw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2kphrbsok.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqqsqbo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkvjqy.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaukglt.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtjjrva.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjasmcvx.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzmdohm.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2oziykbly.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jpajiwcc.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2lizuujmq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkcbkjc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwtmvxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2beqziayt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbhwhiu.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtpwnwb.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvmsazi.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkevhfoo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiwybqe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mytemqon.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsvozrn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2skofaglk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmekdqyc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2awwfetqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhzefoa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsceafum.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fovrzkvb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2esexbqqr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjbgdez.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkftwda.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mylankdn.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlecsyxk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2useilxqd.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoiynyr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxyffuw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzgsffz.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rotrmbvy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vysucxjl.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilndanmz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsbrmtk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zaderahk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrgnetq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2nknlmsgp.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnkmdwz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2trmeztwv.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaambtp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoyrhqm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrqetlm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlkrbrf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnctmoq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2yokikdpp.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhapthm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oljntpmi.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2rshfwdzi.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2loesjimk.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqjnnuk.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2heghpukl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmcujjy.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlausgw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiaoaye.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoqgios.html

Ruby: arr.max;  arr.min
来源：http://dali.zhijiandao.cn/Article/details/gt2decmcoxz.html

C#:   list.Max();  list.Min()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqeamfw.html

[D18] 扁平化嵌套数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sessxtnv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxagwdb.html

PHP:  array_merge(...$nested);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaclwzy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkavfyt.html

TS:   nested.flat();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgctehf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeqtlxe.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gneiyufx.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqrabcc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzrtxsl.html

[D19] 按字段分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdbjfi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjbryg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpylclp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhijiandao.cn/Article/details/gt2plmpsrat.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jynordjb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbabuff.html

Go:   // 手写 map[string][]T
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxghlpc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzpqtbk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gt2qleounqz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmitsvo.html

Py:   Counter(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpchuxv.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxzwwka.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ureaxlin.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwbjwlf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhijiandao.cn/Article/details/gt2zoozzalb.html

Go:   // 手写 map[T]int
来源：http://dali.zhijiandao.cn/Article/details/gt2htxihsbb.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2unpalgzj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgqrljd.html

[D21] 判断是否包含某元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ngshswpb.html

Py:   x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjnmpcn.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiudsri.html

JS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blatyiyk.html

TS:   arr.includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnkzjew.html

Java: list.contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmhakqh.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiauulk.html

Ruby: arr.include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlgiroi.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhgekpm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfstjeh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rradwacc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cttfcyrq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmugofw.html

TS:   [...arr];
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnxzbue.html

Java: new ArrayList<>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2msfcjmwc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtpqgkz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoraeyg.html

C#:   new List<int>(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgskckbh.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsyssyz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lblgwfys.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaoxesu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oydvcniz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptvkifz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqssdntk.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wopkxgns.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkxxdin.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtijbqs.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sozkosfv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2aajkmsaj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpwyahf.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuwdzcn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtacsqxi.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2eonuivik.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmzeuzt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypchbdva.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhijiandao.cn/Article/details/gt2kktgewcx.html

[D25] Set 集合去重与交并差
来源：http://dali.zhijiandao.cn/Article/details/gt2jpojzpxi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsxwwhc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaauimv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2scykapdj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfejldho.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjwjywb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhijiandao.cn/Article/details/gt2goirnlyj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjzxufx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzmyidi.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afxgxwrk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlhxrtt.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpovahez.html

JS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzqydld.html

TS:   arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwwjgxi.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvooyfs.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2whpitbys.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gt2saifcerh.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjdvbon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnziipej.html

E. 字符串处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbbacd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xksiksuu.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnirjko.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpqjzdh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drdteeuo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psditlbv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyfbonb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ellslgjv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyrayso.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuexuyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyfzshn.html

[E02] 重复字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tobysgaj.html

Py:   "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2stdxllew.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwenhx.html

JS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqssjvrd.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2joyhkxkq.html

Java: "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxxinlh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecchwje.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gt2kxubuwja.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrnvpev.html

[E03] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2owuxqeti.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuskvaww.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2njwsswmx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqkfvpz.html

TS:   s.slice(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpanxsl.html

Java: s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2esbrselo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gt2vzifphwe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gt2czurejxt.html

C#:   s.Substring(1, 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjjsyud.html

[E04] 查找子串位置
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfhhxmd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2hplmbdru.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2heifvngf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruricyrt.html

TS:   s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtzjxxq.html

Java: s.indexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhhwqa.html


<!-- 参考信息 -->