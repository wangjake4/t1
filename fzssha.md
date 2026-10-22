代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cesyfklh.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2ybuzdean.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nspwxmbp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gt2gbtfixhv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knfszhqx.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gt2xfugqcce.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2gosexoee.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2tlmnwqei.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2yobhjhkm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ttmmwire.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2timqulqt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2rlukosfq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2jmtberbl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2peutcsiu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2ymgplrva.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2iqpuzsgj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2sjqbtgiw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tmfbxleq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2wdxduzgl.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2fsnprcqx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2hidcdslb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2utmvcvyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2akfwjnzx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2tnyuvsdw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2zzczuyqb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2bphpprzz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2erfywlmi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zblcbhtw.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gt2upbrwfpb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2ogwhmmle.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fhpdafmp.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2qbproamh.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2qxuynphj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2eqihbcet.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2siivupue.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gt2mpzdxrgg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2lbqation.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2mhdfmdxd.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gt2jtdrvais.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2dphypyqn.html

JS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ymdmopco.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2fmqxkvbj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2fyscbolg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2jyiwfucn.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gt2nbbbhjyi.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gt2nweliyhm.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2zegyczyo.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gt2tbbogwwz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2bpatgsll.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2qsvvryrc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjiotgd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jzqygpkg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkeuefax.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2egixrzwd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mewflbzr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gt2auncleel.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gt2iafbvcsi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2fcjplwjt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqiuwumu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2iljffhyv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2tapwltui.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vflzkdtw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2zshkydsu.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2csmrtqts.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2qcmulwkz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2rrxvvjzp.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2qhpumpkr.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2bxslcull.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2wngamhhd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gt2yqrnjobd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2oneqgckk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tanke756.top/Article/details/gt2fapbkriv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2dlrbtnbn.html

[H08] 获取错误信息与堆栈
来源：http://dali.cucudq.cn/Article/details/gt2evlduizp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gt2uhybwxbh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2cgojlbmg.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gt2tydblwug.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.redwolf501.top/Article/details/gt2wcihkfxs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cheryme.top/Article/details/gt2xgqbxsjl.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gt2muypdvmf.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gt2rxgaxewl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2ehavicch.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gt2mmijxfki.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gt2jymxkors.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2dfqbbdhv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2bzogbwgt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cucudq.cn/Article/details/gt2qbpfpjux.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2bozxisqm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2rczervzj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gt2gcsbivwv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbpupfou.html

[H10] 资源自动释放
来源：http://dali.jlsjyb.cn/Article/details/gt2ztyvwrbn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.haohaochexian.top/Article/details/gt2dwhwpaag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2qeyxyvoa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2inufdmed.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gt2rvvdqcvh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2jvgmdtlz.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gt2fnjkghdr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2fzgedhyi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2habvmabt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2byatycvy.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gt2svnkghqh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xclvyfzr.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2rlzogbna.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xesyojit.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2kpmzqagh.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2yawdnjlw.html

TS:   /\d+/.test(s)
来源：http://dali.daria6918.cn/Article/details/gt2gqrqezsu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2anyryrrp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2xkvwabam.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2cyjqlxcr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2fcnyluol.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2sbmrmeuk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2rrewljou.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gt2hnwgliol.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2izzeojef.html

TS:   s.match(/\d+/g)
来源：http://dali.guannengcc.top/Article/details/gt2gdajkhry.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2nliogbno.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gt2qmplsrfm.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2cpotpwhl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2puhjttiu.html

[I03] 提取捕获分组
来源：http://dali.316326.xyz/Article/details/gt2guxqabxq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ybczhkxo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2oosqdskq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gt2clzozcdv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2qybpfqak.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2ohvvqpvi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2axfybrif.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jyoumei.cn/Article/details/gt2tgrpltkw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gt2znejlkmq.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gt2iemjkykz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2pulgrhwj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2ogpzltzx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gt2ghcjbcgx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gt2cymcjjde.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gt2ysjyorwj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gt2jugorsqj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2tovxeoha.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gt2yxqdcxwh.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2ouhnjqch.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj20258.top/Article/details/gt2bdatdrif.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kingjmnb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbvbbigg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhuvrulw.html

Java: s.split("\\s*,\\s*")
来源：http://dali.chenzaomai.com/Article/details/gt2ngbtndmr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvbaoaed.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2xvdsnhdg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.snrcjt.cn/Article/details/gt2qsjurect.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.meibo888.top/Article/details/gt2ukxrakpa.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gt2bpaybytg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yueranfly.top/Article/details/gt2npxglxhc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2zkgfxxup.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vmzdyfwf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gt2bxnozpuc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfwvhbac.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenlongwang.top/Article/details/gt2kwgzczbm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gt2ifrxpvit.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gt2tjzmwezq.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gt2vupajogd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2mvrfswvn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.kuanghao11.cn/Article/details/gt2nratxlac.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2vfsoxtes.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jianghu66.top/Article/details/gt2ezxseiut.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gt2bmflbaes.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gt2kfbwevzr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2zstpgmfc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gt2rgbahaun.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daria6918.cn/Article/details/gt2tqzkpqpd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2tzwwmxtv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2cjqxrdot.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gt2tqmfjgsa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.havefunace.top/Article/details/gt2tngwufgx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.andypj.xyz/Article/details/gt2rkzfatps.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2amqwahpj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gt2hfvicjlm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cpnusvdt.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gt2fswlmcom.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2snjjjqhx.html

[J01] 获取当前时间
来源：http://dali.cucudq.cn/Article/details/gt2zrhnggzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2cwvldyce.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2jptzqmkg.html

JS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2lmmitkzs.html

TS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gt2oadacehy.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gt2puyqyvcl.html

Go:   time.Now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvabpmtc.html

Ruby: Time.now
来源：http://dali.jinqigufen.top/Article/details/gt2wlkxpmzf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yonumen.top/Article/details/gt2ntpqmllt.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gt2wkkyamik.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gt2laxawehd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.smart0.xyz/Article/details/gt2upgxnpll.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2xncxsabb.html

TS:   d.toISOString()
来源：http://dali.nanxinkj.top/Article/details/gt2uzqxqvei.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.vqdsnc.cn/Article/details/gt2rutftchb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gt2opcyppgw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2jprucxbe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gt2impvivrt.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2fsmujmur.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2uyjlqnpy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gt2fwiiasnf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2tkrlqbfa.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2uakiuuor.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2zdidtnxg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ppjwa.cn/Article/details/gt2gqzkosup.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozdpeynt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2pmdtnepd.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gt2blncfowr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2ynarzymm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cashguo.top/Article/details/gt2yksidpfw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hammf.cn/Article/details/gt2mrmjvhqy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2fjwtbsak.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyhjauk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gt2wdbiptcs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gt2wudegefq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2ttsgedxh.html

[J05] 时间加减（加 7 天）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pymhbbgk.html

Py:   now + timedelta(days=7)
来源：http://dali.zhongyouzk.top/Article/details/gt2rtbhudvy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2jmoquvcp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2wtbgmlib.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gt2ldzwhwkr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhengqikj.top/Article/details/gt2qdzlnymm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yndiogoj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhdwnggm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2efgcpafw.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2uifoiaft.html

Py:   (end - start).total_seconds()
来源：http://dali.shzxlz.cn/Article/details/gt2tfribigf.html

PHP:  $end->diff($start)->days;
来源：http://dali.daria6918.cn/Article/details/gt2lrsuxdwj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zdqjudy.top/Article/details/gt2hyfyicrv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gt2srjpzghw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gt2ncybxizj.html

Go:   end.Sub(start).Hours()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lupzjqqa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gt2iedfbdxw.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2uccrkiqp.html

[J07] 比较两个日期
来源：http://dali.zhongyouzk.top/Article/details/gt2dvhvfpls.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gt2fqgqzvum.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xinyue.icu/Article/details/gt2tiqgtsgq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gt2uospxkxr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnxiangtu.top/Article/details/gt2wabitalk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2ikaywwgq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhoulong.xyz/Article/details/gt2hmnxnsmp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2rkcgzakd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpvldfbs.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gt2pzrluvkk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gt2pyclfhjw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yongpay.top/Article/details/gt2wcknlhke.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.vqdsnc.cn/Article/details/gt2bvdqgydy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjwocvhr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gotoacloud.top/Article/details/gt2zzakavrg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2shzvsviz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tianlin.xyz/Article/details/gt2wmzdtlpt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gt2rrqthpzd.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gt2idnoedir.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gt2mfmebytn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jlsjyb.cn/Article/details/gt2mvkxsqha.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gt2hqvfrikr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gt2uljsvwis.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2bnjebxaa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.c1oappe.top/Article/details/gt2whggwsfp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2hilcdhzc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gt2iagidujk.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gt2nhbdnmyf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gt2qdappbap.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hizwurqd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cqqwz.cn/Article/details/gt2ccpvqqeq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2cafhitnv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gt2zastaqdj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gt2rzoxxlkk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2hfmeqjey.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ykbidwjy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2axxvckao.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gt2uxilamgw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2yqcpeynf.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gt2fjvywgjc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyuvkidj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gt2uievrrak.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2eiljobqn.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jewtortm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2holtomzp.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2gtmnplxh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gt2prakehjb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258888.top/Article/details/gt2wxgjdflt.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gt2svwwzzoe.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gt2avdksfzm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnbdfvvp.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2bdkmsdkc.html

TS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2lqnbodpd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2ntsdpfvj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gt2snlrvanr.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkluyykf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2brwtxnbo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gt2ktluuvlr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2dkqqdpvi.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2sodzqdur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2wzghikrt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2ewcnvpdw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2umaolxxg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gt2ovjfflqy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2dkdoaejg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gt2apqlobtu.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gt2oocugtib.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivxiugao.html


<!-- 参考信息 -->