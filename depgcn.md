代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2kfeiujvv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gt2gsxyfyts.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gt2wcftgnwt.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gt2gysuspvg.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2htepymip.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrtlyuws.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2bnsyggsn.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gt2luipudsi.html

ANALYZE TABLE users;
来源：http://dali.sxryk.cn/Article/details/gt2elocesvr.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2tpvumeuv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2grneoskq.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gt2tfpafyeq.html

SHOW INDEX FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2kazdiiww.html

[Q73] 查看表状态
来源：http://dali.jianghu66.top/Article/details/gt2qkeaexyg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gt2sfrvdcls.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gt2ymrykmag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gt2rgjfetyu.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2rslcwfjb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2psuqczdj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gt2kcrdoxgv.html

[Q76] 按天统计
来源：http://dali.hnxiangtu.top/Article/details/gt2lbfddcln.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2tixncwkc.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2cpddamsg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gt2qzusavrt.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2cjdfbgwt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gt2wnxvzgcd.html

[Q79] 字符串拼接
来源：http://dali.redwolf501.top/Article/details/gt2sxewpnob.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2zjxphifk.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gt2qtmpwygg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2pjcxeijp.html

[Q81] 字符串替换
来源：http://dali.ivvv.top/Article/details/gt2mpljnpnd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2fompeszh.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2cyblfdmr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2uortcbim.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gt2wgkkdmtz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otujzgwb.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gt2vulmbufs.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2fotgguzp.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2frxwvips.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dashuyun.cn/Article/details/gt2ybhvgmys.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2ttdylvox.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pengpengdd.cyou/Article/details/gt2yngwhvuq.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gt2gpgrwjaz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2kcilupoo.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2cuxbgbam.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcfoldce.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqqwyawd.html

[Q89] 判断表是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2kkqlfmcg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gt2cboogpck.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gt2napxhvom.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gt2smxgkmhl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2cqbifzdp.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gt2ipzkqaco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oumgvesm.html

[R01] shebang 与严格模式
来源：http://dali.nanxuanxn.top/Article/details/gt2ftvexutg.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gt2wpoyeiqk.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gt2dlmlykgs.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gt2vxocgugx.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2zemvddjh.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2mywemiya.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2eyvacwee.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2rqhgftrq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gt2dzxakfmq.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2eutokaoi.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gt2wfgqdfvt.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2ofsnparl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2ipypozox.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gt2iwjnquxe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2jchrkaex.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gt2epkocdoy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gt2itxgklmp.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2jfaudrsa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2zljrlvqd.html

[R10] 正则匹配
来源：http://dali.xinyue.icu/Article/details/gt2yulxnyqd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gt2cdcypppj.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gt2blcswhlh.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2illuypqy.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gt2sstmkqmf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpaoiao.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gt2dvslaenz.html

esac
来源：http://dali.daxiang520.top/Article/details/gt2vmswxsvq.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfvubxlb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gt2knzahrnn.html

[R13] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2tkgiiiuy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2kjnyivkq.html

[R14] C 风格 for
来源：http://dali.xinyue.icu/Article/details/gt2qamdmrso.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2mvfscifv.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gt2ttwybdko.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gt2fcfpqfqy.html

[R16] until 等待条件
来源：http://dali.c1oappe.top/Article/details/gt2bowxrofi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jewqgqdi.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2ptqiyktb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2fosolgin.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycwvtrmy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytqldxgx.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2mlubafhc.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gt2rhyonghc.html

[R20] 关联数组（字典）
来源：http://dali.svipenyu.cn/Article/details/gt2mifqiboi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2irymsmfg.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2ybfwuxya.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2lxwopeqr.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2ktyhxxcj.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2dqlibkvs.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gt2ielrvccz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2jcrybtbo.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2mjqjtiop.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2cqyjwlha.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gt2slfczdxj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2sbywsuub.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2nkydruoa.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gt2gibgwtdu.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gt2rbhpfhtf.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzgusbhj.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gt2ljbfsrzq.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gt2ogouyxmr.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2kgbmitsy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gt2nhrexiic.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gt2vpwvlmxu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jchyrooj.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gt2zwfhtovb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yj20258888.top/Article/details/gt2zqrydmjh.html

[R32] 参数个数校验
来源：http://dali.hywenlv.cn/Article/details/gt2vhyyklyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2fssnibxp.html

[R33] 捕获错误并提示行号
来源：http://dali.xuanzx.com/Article/details/gt2fymmggqe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gt2mhmghiwk.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gt2jhhlqesm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2wkdqxuhe.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2rbogunln.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gt2ptojsguh.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2nvnscuzd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gt2hfpcftgk.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gt2shtezzof.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gt2iyefcivm.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2xsiemttn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gt2qdctaoio.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyxgzeur.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2erjwzney.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gt2qrikevrw.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gt2ohyvfdga.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zylvpklp.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxvnmcxa.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gt2vpcaggrs.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ejysipuq.html

[R43] 按名字查找文件
来源：http://dali.zhengqikj.top/Article/details/gt2ollrwowb.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gabejltj.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2dvozvlux.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gt2hzjhjpaz.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gt2hrtalmrq.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gt2mxwghtqo.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gt2gckfowps.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gt2hruhqecf.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gt2fcjkrfpc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2nzxzjmpa.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2uvckrcax.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2eukzdwgt.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2jzkufymo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvrfeqxt.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhsgykke.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gt2ffmocuvb.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gt2vzwbxdiu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gt2uaymnbdq.html

[R52] 统计行数
来源：http://dali.kuanghao11.cn/Article/details/gt2tjchaolt.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2oollofil.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gt2ockibixl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2lguzeiwk.html

[R54] 比较两个文件
来源：http://dali.yuxming.cn/Article/details/gt2neygtokq.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gt2bdfxvxhd.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2oifebaav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnqzz.top/Article/details/gt2jzfceplc.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2orejgtdw.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvphttkz.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gt2fhqntmwg.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gt2ijaoooto.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gt2dnblrkgn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gt2lmttfaof.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2wbcnekqm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2ealywcin.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2utlbceuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2oavjamqp.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2llfmccon.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gt2zxhmdbyv.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gt2efdyyikv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2qvkbjveq.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2uixotucn.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gt2wqclhyzg.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gt2avqvwtlo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gt2vlvqiczv.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gt2mlubwieu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gt2lzeigtel.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2hqhoqpbi.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gt2apbmynxu.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gt2hxapuufi.html

openssl rand -hex 16
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sonlulju.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gt2fzyfukdf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2eixqtrnj.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gt2nzzvjjlm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2vvwuweot.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gt2zvqlmmso.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gt2mwveqhap.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2xqvefngd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gt2vhjthexi.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gt2oslzrhvk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2qiwteotu.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gt2uoglhrjs.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gt2wtymltzg.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gt2xmltyxrl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gt2lwgajyqv.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2otmruiih.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gt2tvwjzrwj.html

[R76] 使用临时文件
来源：http://dali.havefunace.top/Article/details/gt2nsvexcea.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2sljllzde.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gt2gblbtiwr.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2stumnjdx.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gt2dptwidon.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2kfjfmlee.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gt2pljxlavl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gt2pkguyhdo.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gt2xqdepkxy.html

time ./run.sh
来源：http://dali.c1oappe.top/Article/details/gt2vltgbvlz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aithmaao.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gt2hydbynnv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ialruxtv.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2aeghwjdh.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gt2rcsemzfb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gt2pdxzioqz.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gt2euvcmvou.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2rhuzgusg.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2hcrqdoiv.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqottlvr.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdfijfzi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2rwihqsle.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgmuhody.html

strlen(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ftcileeu.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2xtyibqqc.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gt2xrkfkpla.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gt2utbysvlh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gt2yqnqeusw.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2uashmfin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gt2neecifdd.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gt2wjmgbggk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2uejgowrp.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhasemos.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gt2ujgiiral.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2ypkvuytt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2qygwwunx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gt2dvheehnm.html

fclose(f);
来源：http://dali.ybcxt.top/Article/details/gt2wqntvcjc.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2zihbavbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2myhfyulj.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqxbqwjb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2ejlpbtsl.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2zunklzti.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gt2ctlxkemn.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2vuxexeke.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2wrcrqkcu.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2byjluemt.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlrdowxf.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gt2zthmhjjb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2yvjembpi.html

[S18] C：命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2qxdganbk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwkjsww.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2uofhhfdt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2urhyzhwy.html

[S20] C：二分查找
来源：http://dali.zycfv.cn/Article/details/gt2pchtxtvb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2shhsyahw.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2lhqbrxhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gt2lpfrjvhk.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gt2xyxhdmes.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyjiglnd.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2mgvfffxz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gt2efjkkyys.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gt2gepbjxmv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boitntfa.html

[S25] C：内存拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2rwvbofjv.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gt2ndpbpqll.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2ayuexivp.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gt2twzpczys.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gt2ihmlcgme.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2hzxlhzqf.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwclbaha.html

static int counter = 0;
来源：http://dali.yuanzhike.top/Article/details/gt2mmavjjzb.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2hmkjwwin.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gt2cwsrnzze.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2qsypqjug.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gt2hxmvekco.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2dvakmvgr.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gt2iovdrkbq.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2xahfyfec.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gt2byzungrz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gt2ayyfuamh.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gt2peptwgfc.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2swmtocec.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gt2gnrrtpbp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gt2rctwkarw.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gt2siftixyf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2ofdpxzvj.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gt2wvnygcgd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2camvutkm.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkzyayfx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2rrrkmlxn.html


<!-- 参考信息 -->