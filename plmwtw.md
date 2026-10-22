代发 wailian999

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2munfdukf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lcukuvbo.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2vcjvaecm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2olxshrfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2owkvsidx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2gvgneezv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2cthxmsda.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gt2cqhxjyxt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gt2cilwvyeh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gt2rvuotqqi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2ufxofqyh.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2kumgpjcv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcqqceq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2omcyuvki.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2rbsoimmd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2kprydgko.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2cdnqwosq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2fhmavrix.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2blpdbgtr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2qruiwcbr.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2epojicqu.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gt2fudwspqa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2mzoydusl.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2tqvuiqln.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2szzuvqzn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2szdurajj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gt2ucpzvvkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gt2jsghhewf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2nogszrni.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2aejorlll.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2qhrclctw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2hptslkjr.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2gdavdjhb.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2mlurakzk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2qxjmxnhh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxyrxvfo.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gt2mogwafop.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gt2huhfvvci.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2eaitnpqm.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gt2dkvshfbm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2hzfrjcib.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2kgpsfunb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2aaipqyfg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2yhonijay.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2abvjwnpc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gt2xcrqorvc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gt2mjpnnffk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2szicwtsh.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2prexndod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2owmqmwcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2ybernjmd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2kevkbfmz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2ijwwrgqk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cucudq.cn/Article/details/gt2jpaqvbrw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gt2rhgousmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2olouhbhf.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2twjustbt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gt2jepkecox.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2ahqvlmkd.html

JS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2alirnipc.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2eofelebj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2azzgwouy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gt2jthiwchv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gt2jxavoxiq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2krchchnc.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxumthlr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gt2sgovnecm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.feifeiyinyue.top/Article/details/gt2gstmiuix.html

JS:   e.message;  e.stack
来源：http://dali.ehwqpu.com/Article/details/gt2plmojkjg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gt2jxevhhce.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2xqwiupxr.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2ojxwqauc.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2zujvogoa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqorawny.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2bhgwyrwg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2ujteykdi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gt2iozgetze.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gt2zyknayxi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gt2icimlpng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dashuyun.cn/Article/details/gt2atrhffzj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gt2sdcyqytb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gt2kfiotprd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gt2xqzjqsyk.html

[H10] 资源自动释放
来源：http://dali.hywenlv.cn/Article/details/gt2qvwjhjfg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2gcmnbtps.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yueranfly.top/Article/details/gt2uoyyidcv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gt2zdjfltez.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gt2ugybmhwf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gt2jkwislzi.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2hritguwn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxuanxn.top/Article/details/gt2uxytnuus.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2xxayvpzp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wicsjdka.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gt2cjsrspnz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2csnryfui.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gt2bjgrnaut.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2ddpiygwl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2nqmkclyc.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gt2vuodyfdp.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gt2vehnqmjs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2kaqegijf.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwxchwbi.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gt2ppsaexeg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2zmchozas.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gt2zhnralsg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gt2klafnhiz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2wrlciyvg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2auvnzafa.html

TS:   s.match(/\d+/g)
来源：http://dali.yuxming.cn/Article/details/gt2eikcdpya.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2rdubpveu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2ogohgaez.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldzkyefm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2fcokcvrl.html

[I03] 提取捕获分组
来源：http://dali.cqqwz.cn/Article/details/gt2wbbmwclb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrfojtsh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2thjzovmt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arpwzsob.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gt2dmuchxqc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gt2gkygzzrt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gt2zmzcvfir.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sxryk.cn/Article/details/gt2eejtzjwq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gt2csvbnqug.html

[I04] 正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2iyonobam.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ydzc1.top/Article/details/gt2civkniyz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2jhrfnnen.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2eeiffgjr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2uajurxgn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2kwynyqly.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.vqdsnc.cn/Article/details/gt2jxshpktf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gt2zweacgqs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndurqfdt.html

[I05] 按正则拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2wzwstccy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gt2ccugtmfl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2mvckvklw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ppjwa.cn/Article/details/gt2bqcfouct.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gt2ncjrfdte.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dianchejie.cn/Article/details/gt2sajpbuoi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2ygpvgtcl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gt2lqmwnrlc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gt2imtgsljd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2mktiyvjg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2mnwqdtad.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gzhubu.top/Article/details/gt2lbrmnscx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2bjbhtpyp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hfpthk.cn/Article/details/gt2aapwnkkr.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wammdkfd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gt2psjotcup.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2cxhhidlv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2bdcexadv.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigufen.top/Article/details/gt2btfzbkeh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gt2lgyfxyto.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jqgufenzy.top/Article/details/gt2ymasmenc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinqigfzy.top/Article/details/gt2lzeojbcq.html

TS:   /error/gim
来源：http://dali.jianghu66.top/Article/details/gt2rcsncabr.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gt2vvsieyoh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gt2hdcgmnnn.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gt2uidncuje.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gt2jmwobhfj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gt2hjxrmchf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gt2oysourfn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gt2mkfnmsof.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gt2zxgltxxl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gt2kyfmjfcz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gt2xeaoklmf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gt2nwqgyinx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.c1oappe.top/Article/details/gt2leysbswl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xawwdcxv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2klcgflik.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2sokhlxub.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rumwokpf.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2nmdxlfuw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gt2farolkdm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2euvyrrwb.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2ekpcxsgh.html

TS:   new Date();  Date.now()
来源：http://dali.bjfxy.top/Article/details/gt2ajcnhhdc.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2mypxqdtx.html

Go:   time.Now()
来源：http://dali.cdnleiting.top/Article/details/gt2zlwutkgs.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2wwtpuymq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gt2sbsujjeb.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2kqeompxd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhengqikj.top/Article/details/gt2jheceyvy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gt2oulkgidf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gogol.net.cn/Article/details/gt2wlfjqaij.html

TS:   d.toISOString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmutxwtu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2evgbqipl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cashguo.top/Article/details/gt2pjjwhsyb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gt2odcsdgzg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gt2epflbngc.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gt2fossrfbq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuanzx.com/Article/details/gt2jblhhijh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gt2euzijrcc.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2ovdhheel.html

TS:   new Date("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2xucgtgum.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gt2qnkzlvxr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2drlrmdyu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2ubcenirh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2eqcgyghv.html

[J04] 时间戳与日期互转
来源：http://dali.wangdashe.top/Article/details/gt2wqpbwach.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2xhtdutqh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangshuangyany.cn/Article/details/gt2socpbkbt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ivvv.top/Article/details/gt2ufjerlpl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2oqatfaoy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gt2zgjqzchs.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gt2acukznxs.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gt2cmffcfux.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2glpwfvfh.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gt2wuzprbzh.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gt2oliwyvbh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2usdikpko.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sysykeji.top/Article/details/gt2wistmwvs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gt2izeqloov.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gt2xpvtawvo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2azbsmlce.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gt2hezxveky.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2yejiurlp.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqeqvkj.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2obpxoonh.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2talmptqx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2gwawxhsi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gt2gpamknkw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgufenzy.top/Article/details/gt2dmhwcbow.html

Go:   end.Sub(start).Hours()
来源：http://dali.smart0.xyz/Article/details/gt2qibzajdj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gt2axqawhdl.html

C#:   (end - start).TotalSeconds
来源：http://dali.redwolf501.top/Article/details/gt2umookouv.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gt2brnveszs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2pzvsbkzb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gt2dqukvgun.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gt2fihshtzg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.9152youxi.cn/Article/details/gt2uihxtofx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.andypj.xyz/Article/details/gt2ncslwjfa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2hhesteja.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2gubpxbii.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2zdutbmvd.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2joklqxac.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dashuyun.cn/Article/details/gt2nnykmtux.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2diqbsulz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.andypj.xyz/Article/details/gt2nfdgbbsg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2nfsmkpxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.fengsongda.top/Article/details/gt2ebamjyke.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2cicgmyiw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2lxhuzdft.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fjxgfpdw.html

[J09] 时区处理
来源：http://dali.c1oappe.top/Article/details/gt2lrlfnpty.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sabrmpes.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gt2royjgbmp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gt2oylzztnn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejurginr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yongpay.top/Article/details/gt2mmrzjsdi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2adlqnaap.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pengpengdd.cyou/Article/details/gt2janebyqw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gt2zdfrnagg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2mqwzefgj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nwbrower.top/Article/details/gt2vfpnkoei.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2kepojvqv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vowrzluf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2pqkjcdmd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gt2declhmsm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gt2hevycugb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gt2twnrprci.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxinkj.top/Article/details/gt2qyofustr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2spdfxyxw.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gt2yhkicesp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ilvavoyo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2eetvqbtp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2ztoaqgyz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gt2obywwyhj.html

JS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2salsizuv.html

TS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxqugzre.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2ygqdvcgq.html

Go:   json.Marshal(obj)
来源：http://dali.gzhubu.top/Article/details/gt2eizqrqbf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gt2lgkwwwqx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2qovmnfyr.html

[K02] JSON 字符串转对象
来源：http://dali.jianghu66.top/Article/details/gt2ueirnquq.html

Py:   json.loads(s)
来源：http://dali.zhengqikj.top/Article/details/gt2dfblbcrk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gt2wjpqfspq.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2jyuqujrw.html

TS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2roddqzmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbhgouhv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2qiwfpqjo.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2blkcgkwm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvrwltvl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gt2axajzrco.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ktltzhhf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2ugixokan.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brwabwil.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2zwmqixko.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gt2uipbupxy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sysykeji.top/Article/details/gt2ddykggua.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2fzioqiqt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2mkkdszux.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2geosbktm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsqoamex.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2whohmzuf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gt2jcmjubvn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2yvdtfyzc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2wvhzxdhq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gt2dmiemsob.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2pqdiporf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2mxnavyjo.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gt2pwhvdvah.html


<!-- 参考信息 -->