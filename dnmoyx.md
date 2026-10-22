代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gttrrclhwm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtwfdgnohh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtlekhgjma.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttesjeoac.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtcdyfynts.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtixrfqxda.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtdcvvzxwq.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gtqfviknui.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtnjigowbk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzcfkxfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gturbvtwhz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtxmdrdzgr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtrhhnvxqv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gthznwjfhi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtzamcikyo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtayikcizp.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtesmgiqmg.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtibaojkxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtfwhdivlk.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtnqrupzep.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtnfdttdza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtngdyetmt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gtcolaonuq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gtwjcyeezx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtkrcdtzdu.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gttyuvdrzd.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtzhpbicru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtyabwckij.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtsfhusqru.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gthxcsuqgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gthpnknxlg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtmpmjxuvz.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtqqfbrpmm.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtkvvgemvx.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtdezdgtmq.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtgkbifzws.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtuulbifpl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtmhjqbbyb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtkutkkrrp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtttdjfhhi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtzwyketgc.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtliiuseao.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gtoctjptpl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtittkkici.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtkdinfgln.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gteieszayw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtxhdvnyrg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtxfcbtqdp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtlzqlebts.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtxztrvbev.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ppjwa.cn/Article/details/gttctzrthm.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtgffzbqsy.html

[H07] 断言
来源：http://dali.316326.xyz/Article/details/gtxfirmzob.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtxemahexu.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtyfelckoq.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtxablkvfq.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtdxaqospj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewwkehtt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gthtsqxicc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtdudrksnw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtalklzmsr.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtthmhswig.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtxcqnmsov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.havefunace.top/Article/details/gtkospquum.html

JS:   e.message;  e.stack
来源：http://dali.iojbl.cn/Article/details/gtjwbngpuf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtblvtjuex.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtceofjnkn.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtxflzdmti.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenlongwang.top/Article/details/gtwxkhwrji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtflfulzyf.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtngdjzqew.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtsdarayie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtvpakitsv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gteyuoqnjv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gtmkintjsq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotiepoqh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gtusfjrdfu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gtzeqwocsa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtphytjvil.html

[H10] 资源自动释放
来源：http://dali.quarkkingdee.top/Article/details/gtmivevywq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258.top/Article/details/gtvohkrjxc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gtuxnbfvct.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtrjejlvrb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgfbegbv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtrawsyrlq.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtnlvknqux.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtmdbmfown.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtyqwbbwvo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoxibggg.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtryphvvja.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtisokoehk.html

[I01] 判断是否匹配
来源：http://dali.chenlongwang.top/Article/details/gtblyufybl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gtylgaphpu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtbibydxcb.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtzfixgnuw.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtqlwrlvgo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.iojbl.cn/Article/details/gtgvknrfwk.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtjqpgcnje.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtloltzzqt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtwcipsjvt.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gtconqlajz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtclqbbfnt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yueranfly.top/Article/details/gtoliwmsut.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtfehnnoih.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gtuxslojqh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtcjgtlaqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttttaapsl.html

Ruby: s.scan(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtploykpqa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtsbmazfgz.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtsxwiplkp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtvjymxrbt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhengqikj.top/Article/details/gtlkezmqhs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cqqwz.cn/Article/details/gtzyaigldq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtjhukrbsx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuxming.cn/Article/details/gtodlcfkzl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tianlin.xyz/Article/details/gterbefbfy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtwrtfxdql.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenlongwang.top/Article/details/gtrmnizzxv.html

[I04] 正则替换
来源：http://dali.yj202588.top/Article/details/gtmqpgdmrp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjtybpsa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtrqdnkshs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtcmrpnpyk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gthmzuxukq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtgyedwbps.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aizwys.cn/Article/details/gtqhqlflvl.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtsflsaydp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtrcllqzrv.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtjkzokgeu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jqgufenzy.top/Article/details/gthesnnamc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtweappdnv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtvqwyjsjx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtfzjbjtho.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gteimkoohl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtccrbzegn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtghivofyg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtgfijsduz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtlcztqfbo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtwrhqbasq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxixkdxl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbvbdsnf.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtyefhdgqe.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtxkeyzpqp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jlsjyb.cn/Article/details/gttslxnxyg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxtykmmp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjmskwfd.html

[I07] 忽略大小写与多行模式
来源：http://dali.jqgufenzy.top/Article/details/gtojjyipiz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtyxxznrmd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtwdvftqvq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtwgesccqq.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtduhuospg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jiagoushi.top/Article/details/gtfaofnhqd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gtxvezxeqe.html

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtyzpdtklj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtfkmigerm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aibaodan.cn/Article/details/gtajwncgbr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gtjzghrstr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarolgaie.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258888.top/Article/details/gtxtxzidxl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtyknrasvn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tanke756.top/Article/details/gtkzbhtoys.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fengsongda.top/Article/details/gtnrglefmp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtqskeinve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gtdtkcexds.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpupuqmrx.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtwzrvevir.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnjwpebjp.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gtezvpjvym.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuetiantiany.cn/Article/details/gtzygssmgh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtdliifcfb.html

JS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtifbfwowq.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gthraabkwq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtuytpmjvc.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gthzpfdxks.html

Ruby: Time.now
来源：http://dali.xuetiantiany.cn/Article/details/gtuqabfnny.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gtsrgpotrj.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gtchtjogli.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gttqhamvbg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtxpddhnwd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gtcvylhatd.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtooogpagb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gttiuifnzb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj202588.top/Article/details/gtoimxsrmz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shzxlz.cn/Article/details/gtfcykpoqv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtdwbdzbfn.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtlnonpfbv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtltpcgecp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gthkoylbfg.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtdwvcpckg.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtnkhqanxl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtdgxlvxbn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtgydvizok.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtdxfowfgp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtsbgltofr.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtulqxmfya.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtysaxyjlz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gtzmjmmfsl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yueranfly.top/Article/details/gtumywtjzc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jyoumei.cn/Article/details/gtsxjrnsnp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gttuvrohto.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shzxlz.cn/Article/details/gtylxekddm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hywenlv.cn/Article/details/gtmovnitnn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtdxiypsec.html

[J05] 时间加减（加 7 天）
来源：http://dali.aizwys.cn/Article/details/gtmaiapbal.html

Py:   now + timedelta(days=7)
来源：http://dali.gogol.net.cn/Article/details/gtrimazxuy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtpapfhthu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtiuizzsky.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtfnlzblnl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtutsrwlfd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtqwejcxkk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtotkvwtzn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gteqqaoeaq.html

[J06] 计算两时间之差
来源：http://dali.jyoumei.cn/Article/details/gtgcxalujo.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gttypkbfrf.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtvroasjwg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtcnhollwg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtgojldntf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtdnysltbp.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gtxdesuzcl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj202588.top/Article/details/gtsxkeitfp.html

C#:   (end - start).TotalSeconds
来源：http://dali.nwbrower.top/Article/details/gteeinlmpw.html

[J07] 比较两个日期
来源：http://dali.ppjwa.cn/Article/details/gtupjijsto.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtavrdbgww.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gtvkudkbar.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtgyklfwbv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtxsvtxzum.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtuinwsspe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkvetjzi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtnhrzpfcn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtitlhxgiv.html

[J08] 提取年月日与星期
来源：http://dali.guannengcc.top/Article/details/gtnayeyhvh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gtgpolwzcl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gtglctbzai.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangshuangyany.cn/Article/details/gtzasrmavj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gteeezagsz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gthlxcjegi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtvnkwnvcn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gttofiymdj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtaffglrkb.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtakmnslnn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jqgufenzy.top/Article/details/gtqrjacmcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtgweomupe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gttozavrzk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtlauxdwdq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcvmgxlp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtiddjpuxl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtsfzzcnav.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hammf.cn/Article/details/gtljqmfpjt.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqigviyut.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtzrewcuhj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxinkj.top/Article/details/gtfllghfkb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gtxrfbiudo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtrsryvnlh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtnorgvklw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gzhubu.top/Article/details/gtfdqoqjoh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtlmvrotje.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtieeosyfp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbjvxkfcl.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gtbhhpksuj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtvwdmhkam.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtcoduqixk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtlucgobnk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtppkbwean.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtthuttopq.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtcmlrxaty.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuhiswvf.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtrubzeirc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtvaxckezf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmuyglkto.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gthqoswuch.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtaffhsykk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gtdksmwhne.html

JS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtalxliotx.html

TS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtlffiktos.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtsezxgchr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtinybixvi.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtfmavnfse.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtkkqysrvb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gtzawzhixc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtcloipkum.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtcraghvyo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterdqjlxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtaxlkowca.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.316326.xyz/Article/details/gtddtrdjqi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zdqjudy.top/Article/details/gthhnyvazf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtphpggaze.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtilfczkmf.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtrmzqwrbp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gtuspvsuwx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarwhlkmm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gtkjahywvp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtttgxvuaz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gttsiigext.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gttyixwrvy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtnrrbggmp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtwveonfqs.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtnaxihoaa.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtgkqlrwdo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtthgtmxzs.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrpsltmux.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtlkbdxfxe.html


<!-- 参考信息 -->