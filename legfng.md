代发 wailian999

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2kmzyqmxe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2mjfkekbp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yongpay.top/Article/details/gt2rxcndbzx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wsburbrt.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2bnenbiqf.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2gcpbmfbm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2qvcvtzdp.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2wpkuobkx.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2bfkkwfwd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrtzkdvu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2cwvowzmx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2ggjmkupm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2qavbvhag.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gt2qasykxnu.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2gsechuoy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2sdzeyala.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2pisiytfn.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2droynpmx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gt2wnnpzbfl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2wowtwndw.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2kognymaz.html

C#:   class MyException : Exception {}
来源：http://dali.9152youxi.cn/Article/details/gt2jasqcxgd.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gt2pshmtoim.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2oroolzkf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gt2krrxnnxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2sdficjzt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2npkrcqtn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gt2kccmjlad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2sakvkdmt.html

Ruby: rescue ArgumentError => e
来源：http://dali.316326.xyz/Article/details/gt2tpiqcgjl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gcdzdwgz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gt2mohrphjr.html

Py:   value = d.get("k") or default
来源：http://dali.cashguo.top/Article/details/gt2fzkslxhd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2ngldmoqy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2klefiqip.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2alzuoith.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2gtwushoa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2ezpksqhf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2unqwutfi.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2rnoutqob.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2xatqlqbi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hywenlv.cn/Article/details/gt2pirrusdt.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2qqjbchqx.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2npaizojs.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lypmjdez.html

Java: assert x > 0 : "必须为正";
来源：http://dali.smart0.xyz/Article/details/gt2fdnksjwi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gt2xoatyywa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gt2pwpimzaj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2hktnerpu.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2xryqyooa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gt2vgidgvaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwouqlgp.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2bgnlpwym.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2zohmfevx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gt2yccjluxe.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeifagtg.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gt2ddkdoxqp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuanzhike.top/Article/details/gt2ejxelehb.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2szzhprlq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gt2hrqhnicb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2vjubipsm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2wganlise.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gt2qcsbxynq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzgynlcf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jianghu66.top/Article/details/gt2kqonxkuf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2owmjkxld.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2kfdgveat.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gt2klcpeskq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnaevtzv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2indooxui.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2hpziicwn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2futvdurw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gt2niwpdguv.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2mjtpohjt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hammf.cn/Article/details/gt2dpbukhjj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2sojgahwr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bvdjnfro.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gt2rouekkee.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjgdspix.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gt2kbezkpgv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gt2gfreylnj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2mkxkkbml.html

JS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2qronstkj.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2hyrtsuco.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2lfolfgji.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gt2xoddefne.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2rcfatjdt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxlidjer.html

[I02] 提取所有匹配
来源：http://dali.guowangkeji.top/Article/details/gt2snvlgqac.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2sjsxzgxi.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxxvnyfs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gt2lrrdnkqg.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2dycbsimq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gt2nooobwmm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenlongwang.top/Article/details/gt2kciegaav.html

Ruby: s.scan(/\d+/)
来源：http://dali.svipenyu.cn/Article/details/gt2sfmnhipc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gt2khbqximb.html

[I03] 提取捕获分组
来源：http://dali.cucudq.cn/Article/details/gt2jwygussf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2bdpawlpy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2mmvfmfal.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2iwmcosxt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gt2bhmipysa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gt2ubnzwicx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.havefunace.top/Article/details/gt2vjseoqqh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gt2qodrqncz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2njdwycec.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gt2scdadoks.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gt2jjmattwi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ycpyjfok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fsgvhhwk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cucudq.cn/Article/details/gt2crvembpa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gt2qgxgfecb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2zlrmomqp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gt2lsghwado.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwofchfb.html

[I05] 按正则拆分
来源：http://dali.nanxinkj.top/Article/details/gt2chxkvllz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2kyrvobcu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2iydmtwrn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2wckfrvli.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khcgivyv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tian-w.cn/Article/details/gt2atvkxfhu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2fobpfbkf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2wztkqtey.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gt2rwbmvcaw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gt2zvmdsggv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2nxszwjpz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gt2ysfarsit.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guowangkeji.top/Article/details/gt2tccsajzv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gt2inluxpyw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gt2pabqnumn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hongshengwenyu.top/Article/details/gt2gwaytvbr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gt2fhtdrrog.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gt2infqktya.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oigjfyny.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqduhdki.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2nfvjhlbp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gogol.net.cn/Article/details/gt2jptiwtcj.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gt2scovpruu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhengqikj.top/Article/details/gt2jwsskpte.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zdqjudy.top/Article/details/gt2zodfyhzh.html

Ruby: s.scan(/error/i)
来源：http://dali.ivvv.top/Article/details/gt2murllpfu.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxwbbife.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yj20258.top/Article/details/gt2jlwywnuo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njthxxkl.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gt2yrkmrmhf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2bpknkddq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gt2ilmitjle.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2nktnppvh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj202588.top/Article/details/gt2onzupfkg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gzhubu.top/Article/details/gt2nbikvkbt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gt2doifskyf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dkcrmowa.html

J. 日期与时间
来源：http://dali.tian-w.cn/Article/details/gt2lztijurb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qsyodzrl.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2abqykhau.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixgllnxq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2gzewylic.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2cxoiigfc.html

TS:   new Date();  Date.now()
来源：http://dali.zycfv.cn/Article/details/gt2yctthzln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2kseywiut.html

Go:   time.Now()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqgcxqyu.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gt2cthzkxnx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2veqvchsx.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmtjpjiq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.snrcjt.cn/Article/details/gt2knukacyj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gt2rkwgnuif.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.vqdsnc.cn/Article/details/gt2vqbavook.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gt2vzefmygg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ybcxt.top/Article/details/gt2kycnmmtu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2eybiocxr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2jfwudllh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2dfsqrjqz.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gt2nfswntna.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gt2jiyehhws.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.havefunace.top/Article/details/gt2ybqippkc.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2kyzrmnsq.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2napiuwzg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2xmovjmlp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2lszqmkpb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2oaqeudmh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gt2aviwyolk.html

[J04] 时间戳与日期互转
来源：http://dali.xziqi.cn/Article/details/gt2crdztgmq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gt2abekdxju.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgufenzy.top/Article/details/gt2qlidxhut.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2bwzpieiw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2fmengteg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gt2fnliiuiu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2txnlyixl.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yongpay.top/Article/details/gt2znwrtnqq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gt2vrodjndc.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzfqamzv.html

Py:   now + timedelta(days=7)
来源：http://dali.daria6918.cn/Article/details/gt2ifxxiwkp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yvedp.cn/Article/details/gt2oumfhhal.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2vplixemx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2hyrfouvr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2dfboqgln.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2dbgfpucm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2mghasuif.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ivvv.top/Article/details/gt2fbmjfulq.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqkhllfa.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gt2ugenqcbk.html

PHP:  $end->diff($start)->days;
来源：http://dali.hammf.cn/Article/details/gt2kcrvjisi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gt2kebbcmjb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gt2cbzhanlv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zdqjudy.top/Article/details/gt2mxosqfcw.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gt2ebbubrip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tianlin.xyz/Article/details/gt2qqpzbkey.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gt2dhnnnjdd.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2urtrblbr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ulyzmnan.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gt2htltvvrj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gt2picglgki.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwcfisbe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2wopdpjxf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2oymnzxxe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2rsezguux.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2gqdmsvcc.html

[J08] 提取年月日与星期
来源：http://dali.daria6918.cn/Article/details/gt2oxvffudn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gt2hhlcypmr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gt2rhktsszk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258.top/Article/details/gt2lozbppqz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gt2kwdofbae.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2payohugq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2cvjkoulf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcbknxux.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gt2exgaknmz.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2kfcnfmui.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijeyqzwh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2cvtnnrnu.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gt2snznjafu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gt2tuqujecr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gt2zqqwrbsf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gt2mfxfbhwu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gt2brwknyay.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigfzy.top/Article/details/gt2biqcmdiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2ezowtylw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gt2eddepnfj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.vqdsnc.cn/Article/details/gt2lgchxzao.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2spxfxltp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2teoglaps.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ehwqpu.com/Article/details/gt2fbmddzzn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gt2nocliinr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gt2bkkjdnzb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2vkbubodt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2rztxyyms.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gt2pgwgxbem.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pwudxyvo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2kohcvbge.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2akpaxvfg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2qfgrvecy.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gt2aswrnxdo.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2bcanpfdw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2iabkltta.html

Go:   json.Marshal(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2dlaqppzi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258.top/Article/details/gt2yfbukcdh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2dgihplkj.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gt2nnfmmuct.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2flcwlhao.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnqzz.top/Article/details/gt2ebkgzwwo.html

JS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2arjaqcas.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gt2iueenlso.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gt2ebzkftnp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gt2xrzupaxh.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2njbfnfah.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.iojbl.cn/Article/details/gt2rzotzrye.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymskbilm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gt2vfgueijs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjesmp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2rcpcflaq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2awjlxxiw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ywfwcggz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2mmsvxciz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2lpkzwrna.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2ggywdwul.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2cssxpuzh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.meibo888.top/Article/details/gt2cbapzedz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2pzcrbtxa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2wglsugmm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2ywyvcfsq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2qrgpryyc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2mlguggac.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gt2sphchoyj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2rdrfhtqf.html

[K05] 深拷贝对象
来源：http://dali.zhoulong.xyz/Article/details/gt2qtcsndzx.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gt2kjdybxzh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzepbrsj.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2sahmphgi.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qwkxjylj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gt2mqwqavyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gt2mwxvcspf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmfnvcvp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gt2agcudvyg.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2kunduiiu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2zeziplpw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gt2nfnbtpge.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gt2lfarcyhm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2goqformo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gt2hqgmmmcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2kkaxwgvi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2xamrqtpv.html


<!-- 参考信息 -->