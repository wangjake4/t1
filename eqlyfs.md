代发 wailian999

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gt2znvqiqiy.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gt2poskkgec.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gt2dbrvfvca.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2dukusvlm.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2duownxva.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gt2tzoxvpym.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2vdlkoctg.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2lfnuevfg.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gt2gzchhxal.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gt2osimncuc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gt2gwzvbgvs.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2vderevjd.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gt2gwdeavvc.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2wfbgceth.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gt2qbmtaimf.html

[Q72] 查看索引
来源：http://dali.gzhubu.top/Article/details/gt2qzybnerr.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2lpakcigw.html

[Q73] 查看表状态
来源：http://dali.xylfe.cn/Article/details/gt2vqnvrxqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2kpzvdtas.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gt2gxojtwym.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.9152youxi.cn/Article/details/gt2xfchsjhm.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2sggjbirw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfbgkpxm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gt2qpkmldqu.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2gifhydus.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2bqxuwsio.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2bboafzxu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gt2dchsjabh.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gt2hhcmswfa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2itobqjkz.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2pdookgmn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.meibo888.top/Article/details/gt2dojjbmjr.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gt2yixcjtrc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2kuqdtgnd.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gt2daxhqahq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2bkkymgmm.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2tthhbczj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ojpkvscm.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2pewkurpk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2yzdhzmzt.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2tbjveixp.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2hlogadbr.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gt2dhefnnrk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.svipenyu.cn/Article/details/gt2zjuejwtx.html

[Q86] 读取 JSON 字段
来源：http://dali.andypj.xyz/Article/details/gt2riimkunm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gt2lagltdgl.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gt2pyadbuef.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cytubqzm.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpugerff.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2exnzwygs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2grxjyvmc.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2wjxqgrbc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gt2wppoglca.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gt2dhommvvj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehfgklal.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2echxfxhr.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nucpekrr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2eiqsxnat.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2jbztlkuj.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2tgpyryvt.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2gdaeyudo.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2aeruultj.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gt2vgjtenxn.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2isuecgua.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gt2qosgwykv.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gt2umaqnfxp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odevzjjr.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvzrilkp.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gt2nlzlqxlj.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gt2qmyiiptt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xslorkji.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gt2dxkylmde.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shuidangran.top/Article/details/gt2rfhrpwgw.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gt2afcpvrvg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.meibo888.top/Article/details/gt2yyccfldb.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdxeabyh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2gncthabx.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2knzkbnqp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gt2lcdmqyei.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gt2aioluoww.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnmexbra.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gt2mslxlvna.html

stop)  echo "停止" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2ffgzrart.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2afdgwder.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2fglqurjl.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2zbydwlah.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gt2ifnsdngp.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2onwnibhq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2jmtljbyd.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gt2cnagikdb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwecbld.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2joaohwsn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2sfswthna.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gt2keenblbu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2lauwbfli.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2nybnbnzl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gt2slljeslr.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gt2eoxssfij.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gt2fiymmuzo.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypcnjlvb.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gt2mrkggscs.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2ageqbage.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkohhpi.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2vfjzrizt.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gt2jucgktcm.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gt2vyvfnhwt.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2hudzwdmi.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2dncanyyo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuanzx.com/Article/details/gt2mfpofsrk.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2efehymck.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gt2czxtpaob.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwnwnznz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.iojbl.cn/Article/details/gt2lygxhjhh.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ecayosxk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dorltxue.html

[R27] 算术展开
来源：http://dali.dashuyun.cn/Article/details/gt2dlpxhngo.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2uunzwahm.html

[R28] 浮点运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prrikykw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gt2ekdlajfh.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqhzyhvj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gt2fcaxmnhm.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gt2wqomzckt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gt2gmowxkkt.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2mpgekxnu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhontqqv.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2pzzemzwi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2wozxuivm.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gt2ubhfewkn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbjyobhj.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gt2wczkzpnu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2apatgoxy.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2cnvitegr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjsackma.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2zreuqbaq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gt2bhjfglzq.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gt2bwkyiujg.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gt2pljhdxci.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gt2bomsetdy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenlongwang.top/Article/details/gt2wqeyecyl.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gt2hfmeqwpm.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gt2mvpdonfz.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gt2pifmghml.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gt2kxbtvowc.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gt2jqqqfzjn.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkntewel.html

[R42] 输入重定向
来源：http://dali.shzxlz.cn/Article/details/gt2elzvstad.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2ajbdkfxg.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2sovgzdel.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gt2wvqihdxq.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgfsbynh.html

find . -mtime -7 -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbkjbqnc.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gt2sjhxdmtn.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gt2jsfwsbja.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2sfozadvc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gt2hqgonqqx.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2olzozttu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2rpqxalxt.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gt2mocxdvqp.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2ymqpsbzb.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2jrnoyqhs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gt2urgklafl.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2lkspbzay.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2hurnboiz.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gt2zvkhxgaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gt2nbflkahi.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gt2ccappavf.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gt2lpznkalz.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gt2qlgnssgy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gt2fgbfcmzv.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2lksyxagc.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoeyimtq.html

[R55] 压缩与解压
来源：http://dali.yuxming.cn/Article/details/gt2uulstzie.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gt2qxsydwog.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibobhltk.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gt2adyyvagq.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gt2csycebxe.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gt2fnpuqfkr.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2jsxcbhsk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gt2fcrznuaj.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gt2evndrbxh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhengqikj.top/Article/details/gt2zqnoqtsa.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjsmowet.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gt2lgaktovy.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gt2ktxqxkmw.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2knzsmlqd.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmllrnzo.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gt2ksoqdyaj.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrycvckm.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2jihfgqxq.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gt2wlrkanih.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guannengcc.top/Article/details/gt2umhsdwye.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2qcvddzew.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gt2civhytac.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gt2ovwuatkl.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvrupvxl.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnyaglsd.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2wilchedo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyytdyq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ataogffl.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2qcnrmmwq.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gt2hnwxosbh.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrfoptqu.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gt2ucmvvkbx.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2mqwapmmi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fzhhl.top/Article/details/gt2pskzhhsb.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2yqsugfic.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2oqxpadlx.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gt2bbvwlcdh.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gt2dwssoagx.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gt2qdubyifd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.redwolf501.top/Article/details/gt2xkflpqec.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gt2xxkutidf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gt2bknabpkq.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmzcjovv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpzvutuk.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gt2dwbnprbk.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2gityfhdt.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2nmexisfw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.meibo888.top/Article/details/gt2ibqcjpgs.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2rnlkmlda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2nlkgfrng.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gt2kqbutwmr.html

time ./run.sh
来源：http://dali.zycfv.cn/Article/details/gt2agxnngxb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ivtqvncz.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2ltiwqvmx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ovvucluh.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gt2qiapqsdh.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gt2cfgzynzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2rquahuvh.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2rauiqywc.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2yeidictq.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gt2boetaabq.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gt2apfazold.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2qrtwzyqi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wotxxdab.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gt2ehlofnyw.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2imywjlfq.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2bzypingl.html

strcmp(a, b) == 0
来源：http://dali.quarkkingdee.top/Article/details/gt2yomhlbwj.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2rjdtjyng.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2fpminuot.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gt2ojxdullo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gt2cdmksasp.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gt2iatnzghk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2nvwlivbz.html

[S10] C：指针与解引用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpllntjk.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gt2fafvwzje.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhgzldmh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acthfuwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2jpxjcicz.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2xzyltedu.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2jjkznnlv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2ozdoipqu.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gt2hoomknaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gt2qnkakvud.html

[S14] C：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2zwmgfllo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gt2updfenow.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2nxnlndpu.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2ijmbrebw.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gt2sekfevsi.html

x |= (1 << 3);
来源：http://dali.svipenyu.cn/Article/details/gt2utetcgkh.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2qancpxiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gt2hnioplnl.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gt2rdulspen.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2hqjdxkcl.html

[S19] C：快速排序
来源：http://dali.xuanzx.com/Article/details/gt2klmgassq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2xpmjqztt.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gt2hpcanznw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2dvgxlnaq.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gt2nflmjhvm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2dizearkq.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2jylgstoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gt2qkckcpgi.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2fwkmnzav.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajqyimsb.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gt2okaazyja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwdkvke.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2laynyqmv.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gt2pnyvzugg.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2yqsqrphz.html

memset(a, 0, sizeof a);
来源：http://dali.ehwqpu.com/Article/details/gt2snarfoch.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2scoyodjx.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2dcnhdenc.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gt2otdmxsyl.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2ptisxmph.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2szhfssbx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2pyytbwaj.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpkalxmv.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2qaoimdye.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkvlblot.html

#endif
来源：http://dali.meibo888.top/Article/details/gt2sfbyfboq.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2wesdxesq.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gt2dhahbxml.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rfyffzam.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxlmzouz.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2edyttrwl.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2aycojbtr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gt2jyntfvbp.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gt2iozmkyxj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vaiqbzck.html


<!-- 参考信息 -->