代发 wailian999

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gt2noirkofl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gt2llqantea.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gt2kogfrwaq.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gt2oihzccfk.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2ibftrogi.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmydmodx.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gt2mkynmicy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gt2uhxkbxza.html

[Q67] 设置隔离级别
来源：http://dali.iojbl.cn/Article/details/gt2hwmlkwza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gt2euyeuxcs.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gt2jyirtyzm.html

SAVEPOINT sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2ioqbgsyl.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2zdiwxqob.html

[Q69] 查看执行计划
来源：http://dali.xziqi.cn/Article/details/gt2zqpfqjme.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gt2zmznaawc.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gt2wytbstdf.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gt2fdfehegt.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2ceaozfuq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gt2gscqokdq.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2xqubsbxc.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ncobqodh.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2lthsjtnx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gt2vsiaklia.html

[Q74] 强制使用索引
来源：http://dali.xinyue.icu/Article/details/gt2aaokiwmt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gt2cqvobeze.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gt2pikwursh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2dcfloaoe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxwdaphm.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2uacrgjqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2occquooy.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2ohcfzysa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gt2goedrxsw.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gt2klqtpsml.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gt2vfscjavk.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2rcrtdyvb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gt2kplfhiao.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gt2xtbnxemk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2dqmhclbx.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2wsydazhk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2sofpopyz.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gt2qvauufij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2iuqhoico.html

[Q83] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2uyaitjns.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjecplam.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gt2mlxjhzrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2oliqxjpa.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gt2cqpjxnrp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2dovvltdl.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gt2kollpgci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2ukqmtzmw.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gt2jhrqvnox.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2axzkbirx.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gt2iqzagxfp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2errfikzn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2lkmegjxg.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2tketexti.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2ezmnvmft.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gt2uamyyjzg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gt2xamuzjwd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ysoduckl.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gt2ksmzwhrd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vktlpsfb.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gt2tytmtqjo.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2nvybboha.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2otteqgnc.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gt2ovowbfph.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gt2xpctsoeh.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gt2iagfgjig.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gt2qrjpkjeo.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2slmjsizz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gt2akjsxiey.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gt2ghqlnqua.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gt2fjecorqo.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gt2ddbzqaes.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gt2ppisjijt.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmmhfqsx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2ivdmmewn.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gt2ksldnowl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2uaqceogy.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2olkhinnw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2fowjvtvh.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2rheeuehl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2zwbdbpem.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gt2zltlnhtq.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gt2xivkdisn.html

start) echo "启动" ;;
来源：http://dali.316326.xyz/Article/details/gt2qpewmbju.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2oscsxogl.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2ycnjelee.html

esac
来源：http://dali.daria6918.cn/Article/details/gt2rgzutawk.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gt2xhjezujj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gt2quqbceoc.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gt2wlgoigjz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gt2waezysko.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2zglyvcpc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2hjkycyvv.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2wvmfecyy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2fwlzuenr.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eauiccoe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2ipqgnuwt.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymeqjrsw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gt2bozebzlm.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gt2lamvbltb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2xhthmcft.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2shhcuand.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2wodfngap.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gt2gbvksvmb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fghtxlpm.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2qyejrljh.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gt2sxrwaxwr.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gt2npqmgypq.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gt2adbxqyyh.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkbrevxg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gt2bfutwgmf.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gt2tgjoybuo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gt2pxcehbjn.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2raoxrzqi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mktisbgw.html

[R26] 命令替换
来源：http://dali.yangfankeji.com/Article/details/gt2yateobiu.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gt2oapkjbtn.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gt2qguabrch.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2mvzcwngf.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtswtopv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gt2rmptnppo.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2irauhyfb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gt2oeuoacbg.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2gamlbbml.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gt2efbsxltr.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2pwtjtfry.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gt2iszilhbf.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2whbanncv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvgzlubm.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gt2vcquoqml.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2ecfjdpmu.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2gckyvhjc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2voahidwj.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gt2ibicndio.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gt2hatdxrkv.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2hrfchbnx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gt2gpvarvel.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2rfqbyved.html

files=$(ls -1)
来源：http://dali.9152youxi.cn/Article/details/gt2tppvksdt.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kasvyjko.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gt2hymamppq.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2buafzanm.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gt2tkyzfonb.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gt2hkfjspra.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gt2wrrbjmgx.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2rbigsmzr.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gt2zmqtbhll.html

[R42] 输入重定向
来源：http://dali.sweek.top/Article/details/gt2eiewaoiv.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2pjucxwxw.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gt2czdolrpj.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2xqfyblby.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gt2ipkzospq.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gt2njfmclff.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gt2mtecgqwp.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gt2fdholzxx.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2xbfcixxj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gt2curzjoga.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gt2imnhvrgp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gt2dbmvalhd.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gt2senctugl.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2fodwuizm.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gt2kyorgsxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2oawcbgaq.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2pgtmivin.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2exrwympy.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2dzmptgqd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gt2orrdpzlg.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gt2kxgyuoyb.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gt2qfhawpto.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gt2oqkbxatv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2avrjegif.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gt2lcxrazyd.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2eeymcyup.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gt2zfbafvha.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gt2rmqdvhyx.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2jotmwlsh.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gt2oarquqsd.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2vnrtxvxr.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gt2knadoxah.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2uhjhbdnb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.vqdsnc.cn/Article/details/gt2qgrdbbci.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2iohygdau.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ybcxt.top/Article/details/gt2iqiverjt.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gt2pygvqxrw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenzaomai.com/Article/details/gt2pkcxyilg.html

[R61] 磁盘占用
来源：http://dali.dianchejie.cn/Article/details/gt2avltclqp.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shplcefl.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gt2vezcabep.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gt2ufktdpam.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2wiohyftk.html

free -h;  ps aux | grep nginx
来源：http://dali.xuanzx.com/Article/details/gt2uoounkhw.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gt2vlpgvssv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gt2uyyzgmbk.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2hpzczsju.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gt2keuvnphk.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gt2zknsqqsd.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2tsyyyzee.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2sntikpnm.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2nzujwlxi.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gt2usuwmjys.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2tofytdpr.html

[R69] 生成随机密码
来源：http://dali.guannengcc.top/Article/details/gt2etfmbcxg.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2xibbrodn.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2pwdqpbby.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmfjddb.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gt2rnjggstk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2qxjietve.html

[R72] 等待端口就绪
来源：http://dali.smart0.xyz/Article/details/gt2dnfmruuu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2wnmysdbv.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gt2xbisbvwv.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gt2xwfbbyen.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2grfksgkf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gt2ywwsnaua.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nnufgptj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gt2dnfbyowc.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gt2epyqpbsm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gt2mupuksxo.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gt2zyjegrwz.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdrjrets.html

[R78] 交互式菜单
来源：http://dali.jinqigufen.top/Article/details/gt2hcesdkbt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2otsalboh.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gt2nmgftkje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gt2zluhtdvn.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gt2sdroqdlu.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2exhiijlo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrvusffj.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2zlwqfspj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zgtaarrs.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfhzvuvh.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gt2jvrsgiyb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spqvtvjy.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nomobmip.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgdphulx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gynkmjqh.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gt2onaghvzx.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2oofdhldm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vztwslcj.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2lwswwndh.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2nzsnvaxs.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2mxgqesnz.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2cgourosx.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gt2soruhmxi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gt2kvccqluh.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2hghappto.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.bjfxy.top/Article/details/gt2bjrbqduw.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2lemazvuk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gt2yppvigyo.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gt2wlbfbeyv.html

int *p = &a;  *p = 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wshearhv.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gt2etrvddfb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shzxlz.cn/Article/details/gt2jioatvuz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2fsxrkrvb.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2mlkvijes.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2kerdlgbm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgfixetp.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2iaybsucy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2oinwodqf.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gt2zofxiinj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gt2bvnvpcej.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2iitlnhnk.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gt2qcczrumi.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2bobybkjq.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2atnfcdir.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upowvmqw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gt2fsswybxo.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2nxdptyrf.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gt2owannxhv.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2yyfzpbwb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gt2fxvidnzo.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gt2grbpyfxy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2ccmifllm.html

[S21] C：字符类别判断
来源：http://dali.smart0.xyz/Article/details/gt2jzlmjkba.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2ctklesgn.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gt2scezcmgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2owqqqhke.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gt2eyfohqin.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gt2vasxgulk.html

[S24] C：获取本地时间
来源：http://dali.shzxlz.cn/Article/details/gt2tbyiergv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2gdvsqfqn.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2utyqpwya.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gt2sjfzkybz.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gt2nihfrgtn.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gt2ddbquxsn.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2tbcosnju.html

const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2xynpgpck.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gt2ejbvgqox.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogqyyhof.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2hznvmczz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdcpzmek.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gt2gpugjfvu.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2eipifgae.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gt2tbnwixqu.html

#endif
来源：http://dali.yj20258.top/Article/details/gt2zmpgsyoj.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2retyglfj.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gt2rguvelow.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gt2efpczmha.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2aamtlzts.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2kmkogbnf.html


<!-- 参考信息 -->