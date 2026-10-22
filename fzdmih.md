代发 wailian999

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2wlhldcpo.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojpclsbw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2motpkwmk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfucxznc.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2ciecfzpd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2rovagwwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2aejydriy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gt2vxinlmvn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2lxchrebq.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2jnaspfcs.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2xghfheom.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2cajxajqb.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rdgoiqyp.html

TS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2hdccwcpx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2jiypsyed.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2yznvnskp.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gt2ibqjbiob.html

C#:   class MyException : Exception {}
来源：http://dali.fengsongda.top/Article/details/gt2olnrgnqr.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2nvcfkczt.html

Py:   except ValueError as e:
来源：http://dali.pycfn.com/Article/details/gt2rkjsywwd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gt2qgpgqwyn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2dtvqpukg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2gjmrjmjm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gt2twfbafnv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gt2xmiefgun.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2wkphopgh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gt2wsczatjq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2ymjzwpsc.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gt2nsjidjys.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2vrfmsnga.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2crrvggdx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2jjacrpep.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2ehvhqdms.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2aypdjwla.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2khsrrqdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2tytdnkfe.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2noftbdio.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2zmjbtkmw.html

PHP:  assert($x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2usgksllg.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2dcbuwrnq.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2gkzrcetm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2tymigqos.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2itcynyth.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gt2jkgoekqp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2qlkxhwyd.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbdkovpn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gt2hpbblyxk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2eafuknxk.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2dyjiltlo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gt2pgnilywf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2oknteibm.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gt2isgbyjig.html

Ruby: e.message;  e.backtrace
来源：http://dali.gotoacloud.top/Article/details/gt2hhfdzduy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2mghsajse.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqkpcjqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2nswzfgra.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.iojbl.cn/Article/details/gt2hbricdas.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2yqardggz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2lbcxfkjk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lxatsqni.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2fywalrfk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gt2ckeexxop.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2wnxzcvxv.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewmxkf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gt2ztsflwos.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.c1oappe.top/Article/details/gt2zgzpzuud.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gt2nmzxlpue.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2rhkdsvab.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sxryk.cn/Article/details/gt2ayvxtqhi.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2ukunzvco.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tknindec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ynuigrjd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2wtgorxyx.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2vvxyjpqk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jpqisyef.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2vxzsjapz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcwhktmg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uusfeimo.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2fuqcznny.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2xixinhqa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.fzhhl.top/Article/details/gt2kbzjyjzz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2vqefjfmx.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gt2eltxihnf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2aonghnus.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gt2siiupcnf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2mbtipmlv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2njvflicr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2fetunefr.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbujoyjk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyksvtps.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubhmkrj.html

Ruby: s.scan(/\d+/)
来源：http://dali.cashguo.top/Article/details/gt2aoomstxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hsgtxajn.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gt2kbvhyfus.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ynecpcsh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2aucctmez.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncgjreda.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gt2oxhurrdq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2nlzavcnb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2ghqwewsf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yj20258888.top/Article/details/gt2nghwxtmi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cdnleiting.top/Article/details/gt2ymlzqqqj.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gt2uprwlpyk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gt2ypixendo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yibvvfhw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2awgjpfyf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eytrjybl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2bxnvussm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gt2gpacemjn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2bmwrzfcn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2vssxgrjx.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gt2wfwjbktl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gt2rnvoitok.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2siygflkm.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmonnqux.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gt2whbibyuo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinqigfzy.top/Article/details/gt2pxbuvjrd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gt2pkmlyuvg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gt2uzvtruse.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2qiihkxrj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.tanke756.top/Article/details/gt2gcpshpbv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jlsjyb.cn/Article/details/gt2konuhfof.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhengqikj.top/Article/details/gt2rflzybdp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xziqi.cn/Article/details/gt2yiacdbtj.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.xuetiantiany.cn/Article/details/gt2dptlovrp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.zhijiandao.cn/Article/details/gt2owgvoerm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gt2hrhhesih.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gt2xhgwxubi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2cmgltcyw.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gt2ptdhrkki.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nwbrower.top/Article/details/gt2jnrpipto.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2kenfcbbr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gt2nrzhbedk.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2dacwbgma.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gogol.net.cn/Article/details/gt2noawzyoh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gt2uiueqmgd.html

Ruby: s.scan(/error/i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxnouvrg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gt2xvwbsqpv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.gogol.net.cn/Article/details/gt2esfodbro.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2bhyguoje.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2schlhnfl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2xwnclabk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acvayvgn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2dnipvoxu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.316326.xyz/Article/details/gt2rpklyccy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.fengsongda.top/Article/details/gt2gxwkfjmo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2qwvuevsu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nyihcafz.html

J. 日期与时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbsvjkup.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hsuypgdl.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gt2btoqnbvt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.redwolf501.top/Article/details/gt2wnzgitwj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gt2sfeldvrf.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gt2zkkahghz.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2ddopbowp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cheryme.top/Article/details/gt2pzmmsgiz.html

Go:   time.Now()
来源：http://dali.hammf.cn/Article/details/gt2wwozqlep.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwejnadz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yvedp.cn/Article/details/gt2rqttwbwg.html

[J02] 格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2vbinrgms.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gt2vnhgsjfc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gt2unbteomu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sweek.top/Article/details/gt2xddsjvvy.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gt2dnrblvno.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgufenzy.top/Article/details/gt2tnevsiro.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gogol.net.cn/Article/details/gt2itpxcwly.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2vzwveivj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gt2bfgpjxee.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gt2wmuapsyl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gt2lblplscj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gt2qzegjfcv.html

JS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2siplazjb.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2aduhhbsb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2sqdslfrr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2ptlguezz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2znxkshaq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmbbscct.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahowjjii.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gt2zdwwznbo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinqigfzy.top/Article/details/gt2gbiaozbz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2xnjqanql.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehkphovi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2itrpsjbc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hammf.cn/Article/details/gt2qbwifsbi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gt2mdmrhpcd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dasdtbnn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigfzy.top/Article/details/gt2vcwjpicx.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gt2mupytcyj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gt2dekkwdzd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2llyxuadg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2tjqehltj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gt2hjiktfrt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2ntxnijmv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gt2hsacypdt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gt2lnzdeijk.html

[J06] 计算两时间之差
来源：http://dali.zdqjudy.top/Article/details/gt2vvjrjzlb.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2rvsnwnyl.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gt2desjgcyu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sweek.top/Article/details/gt2taxkiwho.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.andypj.xyz/Article/details/gt2ftxqgcmd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sweek.top/Article/details/gt2fwrcndwf.html

Go:   end.Sub(start).Hours()
来源：http://dali.redwolf501.top/Article/details/gt2kmpivdyj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gt2qppcvdnd.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gt2rsyefypl.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvffmps.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2nfrzbvwd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gt2fjesihtm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2bumixxgp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gt2nfmnaddp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fzhhl.top/Article/details/gt2voclcynw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xinyue.icu/Article/details/gt2neflgedf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pycfn.com/Article/details/gt2mguqnvjj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2uzzhznps.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvwwjrfa.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gt2arbrgovq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gt2rbqvjoty.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2wxtkkivk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbwwoewt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gt2xtexlcny.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gt2xiyyeqsv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhoulong.xyz/Article/details/gt2eifglqtr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gt2uqqpfaej.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbtwheut.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gt2divayiql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2hlfezjdy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gt2hnhmnuce.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2upgacexr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqndqtmt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gt2ourqtwue.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gt2rlsdsree.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2pooofiyq.html

[J10] 取今天 / 本月第一天
来源：http://dali.cashguo.top/Article/details/gt2jhbbuxic.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gt2dkmhvdug.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ydzc1.top/Article/details/gt2yhefqszx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2kuoklnka.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2krtdcexo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gt2uemgenxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gt2qhxhhiut.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hnqzz.top/Article/details/gt2rxquyycs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gt2ltlrnfya.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wphxveml.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2lgnmqdyu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kozvvbbq.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2nawaazlf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2hxuqonvj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2vulwquli.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2kmqvdgdd.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2fyjmntmx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gt2orcrilnt.html

Go:   json.Marshal(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2vlzmgqjx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2nauudvzs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2acxtnugc.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2xltjifwf.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2tmwhgrqf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gt2tyqztdho.html

JS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2lmnvllyi.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2qczhppby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2cgvgqatc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2bhaaveks.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2lfwswavx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gt2loztsyap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjppnhhs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gt2jlushukg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2enhtpshi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gt2urqbchbw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2mstkwspf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2fdmbkbsn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2yahpjqwv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gt2jqcuanyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gt2dylwabla.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gt2etmzipgv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gt2snjvvssn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gt2ielzhteu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnftcbtf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gt2fprtjqdr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2htrkkjgr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2tlzlmkwi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2rbyfpgvo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gt2kkyoxmdg.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gt2vmvdpyev.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2qlxlxixj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2bwjeeruj.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2chkqvpbi.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zrguhpuz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gt2vgqrdhwp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gt2ywlynryz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2twwihtmp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gt2pbievams.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2aelekora.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gt2wdcdmppf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxpxcwwc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkgangum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2mptiqzfq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2qnzwjcve.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2enplcyam.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2hneeydwa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2jvfjhwnh.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gt2abfkefbv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2mfqcmyhu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2kwfrtumu.html


<!-- 参考信息 -->