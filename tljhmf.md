代发 wailian999

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2qxsmbich.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gt2owbdhqmp.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gt2gpxtvnfn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2gcvlkeef.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gt2zqafjllh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gt2yrnclpov.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gt2pzoeujmr.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2cxyniqpb.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2crnfcbch.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2cxhecbga.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gt2xedjaobk.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gt2xvjwssfk.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gt2gcdfvmkp.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gt2spiwaupa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gt2jrmwgvsd.html

[Q72] 查看索引
来源：http://dali.jqgufenzy.top/Article/details/gt2vbffkzjs.html

SHOW INDEX FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2sqkvpuop.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gt2tjyzbypf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gt2pepvhgxa.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvfwrmvo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gt2mgdjgthk.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2ifwwecby.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejxwyncm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gt2noremcbv.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gt2naxlkxdl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gogol.net.cn/Article/details/gt2bsxpzpuk.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gt2qjiyoero.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2kiuxogyb.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2jsynypby.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gt2asidzlig.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2cjvzpizi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2zrhpncuz.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gt2yqyhrwjd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2lvijnnpg.html

[Q81] 字符串替换
来源：http://dali.cashguo.top/Article/details/gt2wmsvpuzh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gt2vrsipkgf.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gt2mnmkjygm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2tbkraijv.html

[Q83] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2tgcggzch.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2warasyvk.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gt2znhjqchs.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2jwqpvrom.html

[Q85] 数值取整
来源：http://dali.aibaodan.cn/Article/details/gt2rxiultjn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gt2xqlepzdy.html

[Q86] 读取 JSON 字段
来源：http://dali.tianlin.xyz/Article/details/gt2vqlucezs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gt2oataquwx.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2slygateg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gt2rzfxvevx.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2anrjnrvt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wapjthhb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjehhwox.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2qzwfiqpo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2tnyzjnnp.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2urrlgogc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2tkeioufo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rfhwqowx.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gt2klvobyjo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2rbgxkqhj.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2qlnqvbgu.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gt2xgfwnnxa.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gt2kpsntlgt.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gt2pcokhyjf.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2bctkkltw.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2kteewvpd.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gt2tglceopf.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gt2nfnmdwse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2zccwvyyo.html

[R05] 参数默认值
来源：http://dali.chenlongwang.top/Article/details/gt2afllvtvb.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfuhmoaw.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2iihovfaf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gt2diiqhnxr.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gt2tulmbckj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2hdfgauqu.html

[R08] 数值比较
来源：http://dali.fengsongda.top/Article/details/gt2nlnozuvq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gt2fvpfosxy.html

[R09] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzstjwgk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2zsohwjmm.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gt2imjgjxev.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gt2yqakjgcd.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gt2nqfflsnx.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gt2jcelksoj.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gt2hcitweno.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjwzbtws.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2eypubuxk.html

esac
来源：http://dali.0kj1m.cn/Article/details/gt2lkqaykjx.html

[R12] for 遍历文件
来源：http://dali.andypj.xyz/Article/details/gt2bexsnpoi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gt2sjtwlbob.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edrmqaee.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2kvurfkui.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gt2vonuvrrw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2bkdprvci.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2hvsgisus.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2pjgnpjkk.html

[R16] until 等待条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2suvkroye.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2kcqwkuwo.html

[R17] 数组定义与取值
来源：http://dali.jinqigufen.top/Article/details/gt2ukggapou.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nwbrower.top/Article/details/gt2kmcjvwak.html

[R18] 遍历数组
来源：http://dali.jinqigufen.top/Article/details/gt2pnvhloin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gt2drfhcoiq.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2qidfglpn.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gt2ihyurres.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gt2qscnhgxt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gt2tyxmeolt.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2chmlubfg.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2qqpiecgl.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2vaayxxeh.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gt2mbhggtyr.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2owtkpxdw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gt2ozfgpdlw.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2eomjadty.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrcxsvjo.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvmnxoty.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2plljqcie.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2znqjnaid.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2iblzblia.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2jtcauvzj.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gt2fatrdsnf.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gt2yrkzxikz.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gt2bgjiarxk.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2koywvjjr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsevkngn.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2rhrchvkv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gt2ujblakcg.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gt2vqhbjpux.html

f() { local x=1; echo "$x"; }
来源：http://dali.jyoumei.cn/Article/details/gt2gkvmqhuw.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2gwrplkje.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gt2wqzlmqgv.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2evmkyltv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gt2yorljshy.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gt2qaqvdtou.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2fvqhsqpb.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gt2fndmurdw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2mzjnzyrk.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gt2owaxkjur.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gt2odizuxld.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2wqjgdhwu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsivtnns.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gt2qbfnyhqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gt2kzjkkfmm.html

[R39] 重定向标准输出与错误
来源：http://dali.hammf.cn/Article/details/gt2gvccplqn.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2ztlycoap.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gt2eoacekwg.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqfwatzk.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2lqipurcu.html

cmd >/dev/null 2>&1
来源：http://dali.gogol.net.cn/Article/details/gt2kmdfnjlg.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gt2bwzocpyk.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gt2jbqfasew.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nynyqqex.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2hxdlujmi.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2vwgkpdpe.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gt2jtafmczw.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gt2ofdjfufs.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2karttquk.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2cestkvga.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gt2gzvmxrtg.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2qtcjcbsp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2uqiwfwhi.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gt2drhfqdcf.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2ifalekvr.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2kknjbgjz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gt2ftqudjkz.html

[R50] awk 求和
来源：http://dali.pycfn.com/Article/details/gt2pjwiwcow.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2svwxfifv.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gt2nybvbinf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2dkjljrep.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2vwihkivf.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gt2ivynoyfp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhongyouzk.top/Article/details/gt2qungoqeh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhengqikj.top/Article/details/gt2hkwsuufc.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gt2xfkdidxy.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jwtsvbwt.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2ivcvdqfj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gt2fhzzoyxu.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2jodqtgeg.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2lroudmdp.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqaromml.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gt2hqvepnty.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2dtglojsg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2hesvkrqm.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gt2ocjezhmb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gt2wxxxzbpj.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2xchthhdp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.fengsongda.top/Article/details/gt2evioirrs.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gt2qazhwlby.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2tdypmmvt.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2wnypudhf.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gt2iawmahan.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gt2ucqsuxvh.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gt2vzbvhvak.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2euwrmzpe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2nrkamsol.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gt2fzxqnfrl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyndzqgs.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2bjhnhidd.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gt2uoehledz.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lizfqteu.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2vmjttytj.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gt2yrsksrks.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gt2xwkwlrqn.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gt2nzjbcgun.html

head -c 16 /dev/urandom | base64
来源：http://dali.sysykeji.top/Article/details/gt2mcsqaqsj.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lidyhfti.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gt2ibgrpufy.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2ebyipciu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gt2rkizvfdt.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gt2fkigktbt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2fsxelyxj.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gt2odoyreda.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gt2byvebzrx.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2jxdfwvfy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gt2hjwislzm.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2thuznzbh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gt2vepymrrv.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gt2kqvwvhgk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2oazylqch.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2nprmkbrn.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gt2jpyxhozo.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2jizsaidh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwjzljnv.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gt2geaughon.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gt2ititzfng.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gt2rzreksvj.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gt2fhpdfxye.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ufyepewc.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gt2nweepgsn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2clhpgbsr.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2mufswvii.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2vnlbclze.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2kugkzole.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2toysftxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gt2jcfvfxrr.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2gebehocp.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hoqraggj.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gt2elpagluq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gt2wrcxfmby.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gt2shybekhp.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gt2uqikiddd.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2vynsviqm.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gt2fvimqdnu.html

[S07] C：数组遍历求和
来源：http://dali.jiagoushi.top/Article/details/gt2ebgfxrdh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gt2ljgfcugw.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gt2camjrlsv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2uuonejxr.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gt2fzzvdfwo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2uinuejhy.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gt2xcikrpcr.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gt2cedbuigk.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2xrzzuman.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gt2dwkruhjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2hjsxsczw.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2aabkrniw.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2cnajhzlu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2yimuhhjy.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2dwwzcwnn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gt2vzqqidei.html

[S14] C：枚举
来源：http://dali.xinyue.icu/Article/details/gt2kgnaiozj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2eakpdirz.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gt2vhxrbqso.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2xnbluhii.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gt2qbncvlri.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gt2rfxenbwp.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2hszfguva.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gt2omahlaxv.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfnnzrdh.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcttjbnm.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2zwbijzpc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2vglxkpep.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gt2exyudxrq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2phbrxyre.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2jypoexjc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2xlaeurjb.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2isekccwu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gt2okeuvaaz.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gt2uhyivpql.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gt2sdtnmkzn.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxwvbngp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gt2igtnxjxi.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gt2hpxpndet.html

memcpy(dst, src, n);
来源：http://dali.kuanghao11.cn/Article/details/gt2bnyjlfze.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gt2xqnoyjrw.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gt2saxngwux.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2dbhsnfmw.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gt2bdyhrtde.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gt2oussrnsx.html

static int counter = 0;
来源：http://dali.hammf.cn/Article/details/gt2trchjjss.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2ylwxgpht.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2odzxwlhc.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxhaxvva.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2yksjhmnx.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2oqbtfpko.html

#endif
来源：http://dali.yj202588.top/Article/details/gt2moqzrdgg.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlvgtrpd.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gt2tyiooyxb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2vtjlvixm.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gt2mbovsyat.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2yuwvsaml.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gt2nklwwhty.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2wehrhugz.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehwohwlw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lesvqwpf.html


<!-- 参考信息 -->