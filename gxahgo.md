代发 wailian999

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gt2kzrfxlsp.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gt2xsadqyak.html

[Q66] 行锁查询
来源：http://dali.hywenlv.cn/Article/details/gt2ygryhxhs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gt2aqsgdhbd.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gt2aninvkli.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gt2wwqbrpfb.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gt2pdppmpbk.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gt2mevmkmsk.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2ssyfiqhl.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gt2zribyoah.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2qamzaznp.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2dvwdfcxf.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gt2mjseweza.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gt2yxrauixz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gt2hcosunjk.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gt2qkazgsaz.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2kulzjibt.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2qrmemneh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmheshon.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2dvbpjoyg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gt2odgkaplr.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2abzpkszp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2kgbhtmkm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gt2pegerhlc.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2wxwhmnjm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gt2shlifidr.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gt2eyvbwvgz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gt2lnipnlck.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gt2yzuoufym.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gt2mvtizrjs.html

[Q79] 字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2wfhgtqzb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gt2gkvhxzhb.html

[Q80] 字符串截取
来源：http://dali.hnxiangtu.top/Article/details/gt2kwgurdxp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2mysoamgl.html

[Q81] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gt2cygnagxa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuqofcvs.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2zxgkmkin.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2trqaecfm.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ykcczsmt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2vilddefn.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwehjnos.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2nuaadbnt.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2dcobxxvw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2kuukhdhb.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gt2cqerhoqx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gt2nxsnpgyg.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gt2sjxdwkpv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gt2bjzesiji.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gt2coegcfuc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gt2zxalydeu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2qfdxoqmc.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2umrihkpn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aibaodan.cn/Article/details/gt2ggbauode.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2ijedpfli.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gt2lbuyotib.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ctcqzues.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gt2kwkofhtq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2jftlijjn.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gt2suxumklh.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gt2qhpneues.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gt2inebvkmf.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2nppipxef.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gt2szpuamtp.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrcrolzx.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gt2ylfneyfa.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gt2aqlbxsej.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gt2kqmokkie.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gt2uxfswdhf.html

name="${1:-default}"
来源：http://dali.zhengqikj.top/Article/details/gt2keaorjpk.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2wpepwinv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gt2cyrlmfnm.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gt2faxljisq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gt2liuipzre.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gt2ovknfovn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gt2ilaxuuvu.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gt2soojgwzu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gt2kibaqodn.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gt2roccxavl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2xjlyftcp.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gt2syrejhxx.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gt2mfevozbe.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2hfwubtqo.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gt2faukojan.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2avgnwxlz.html

esac
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvdybgkx.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gt2dgdgfvob.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gt2ymehvknm.html

[R13] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2btavvapu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2bqrcsjxq.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybdoxjsn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2ewqlpjsc.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2gqquepdb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2pwlqouha.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2cmwrvgsb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2stgcwvrr.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gt2pdewzlwi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2fcymgtxd.html

[R18] 遍历数组
来源：http://dali.sufxvd.cn/Article/details/gt2jtprrcpw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2vqudskbt.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umsdsyoy.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gt2bnvbhjvx.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gt2imzkltlr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozywtcdd.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcmiqcaj.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyatbroh.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gt2wbaavdpz.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxemiiur.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gt2ofjpwzwl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gt2hxxajktt.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwhuvujt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gt2tlrrsonw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tojxorzc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2pltnfwyx.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2tohvhsdw.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gt2vwzidnqh.html

[R27] 算术展开
来源：http://dali.gogol.net.cn/Article/details/gt2fvbbruaa.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gt2mqcoeewh.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2ydkaprue.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gt2feekmidk.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2heavsxxj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dashuyun.cn/Article/details/gt2pkjhglmy.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2xklyjplx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gt2xequkwxg.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2qwttsste.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2zkxcfsoo.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gt2rcodfxqq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfihzuoz.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2oygmcoeb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gt2slwvgizu.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gt2lrlugctl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2qijtwkdz.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gt2ixmbtbqs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gt2avvejwvp.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bavjpymh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gt2ttkmwsqi.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2cbiiwjwb.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gt2xelcvjau.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2uxrymnch.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbfwaybr.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gt2hnnruxpm.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gt2pguzzvbq.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gt2ihpozchs.html

echo "log" >> out.log
来源：http://dali.yueranfly.top/Article/details/gt2fkhwpxwj.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gt2gctqgaov.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sazmvbwf.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlfpiltt.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2mkchemus.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ktljxhiu.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2neqxbobw.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gt2wzkixauo.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2rhxffdha.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gt2xeidyjcg.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gt2feubulrr.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gt2dhxosadt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2lbrlhzeo.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2labcqduk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2arokmzxk.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gt2qlbwqeqr.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2mlnemuiy.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jizrjldm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gt2zirkzivo.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2cyefhtzb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2djpcwwkz.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2cgdymcxc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2jlnkqrlt.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gt2xjjuxhgq.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyvceiib.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gt2omugtxzl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.kuanghao11.cn/Article/details/gt2qtncgdpb.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrgcsyfi.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2ayanjhox.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gt2ikvlpeoy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gt2igyherxt.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2rhcqkjww.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2tsiffadl.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gt2dkycdowb.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2wkpqbelx.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gt2ujgadeib.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2zodvkyqv.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2reshewbl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2olcvztfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2snyocedk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gt2mtmjkdpq.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2vxxjlsqp.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gt2bkagsdwi.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2eotdruuk.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gt2avzxtipi.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gt2abqrbavu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2yfrhwnff.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gt2yahazpen.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gegtcjxs.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehynkctg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2qzfyegfw.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gt2yqhpjhpx.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gt2otillxqt.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gt2tofoviso.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gt2uhxtwilt.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gt2wxqscyyj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2eruvsbxz.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gt2mgyxyzre.html

head -c 16 /dev/urandom | base64
来源：http://dali.ydzc1.top/Article/details/gt2gkxgejpr.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gt2rfwgxlim.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gt2izrwowmt.html

[R71] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2zlrdotrx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cgyhiucs.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gt2dyhnyenn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2axuzkmay.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gt2ugiaphis.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhqeuxjt.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gt2tcrpwpri.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gt2fuctkulh.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2poqwyiun.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gt2wkzewcfe.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxdypvtw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2rwdlzete.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2inrcjvnj.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gt2yhhienqo.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gt2wgqlbsap.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2bnxidnoq.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gt2jhdgdcbd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gt2docoehtg.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gt2mjosgdaz.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gt2tnoaxgzm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ajjxudjo.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2iegocngy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2amjsdfst.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2adplkzpx.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gt2zptcjyrn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2jhbqqqsq.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2ppejjbqw.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gt2hiwojjbq.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gt2twexegrv.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gt2vzkjbset.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gt2mriabppx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2ucwmnakj.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2lbhdasiz.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovspptid.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gt2hptlxxed.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gt2nxwvfecm.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gt2xsjutqmf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gt2jwhiawsj.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2epbbyqsj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cqqwz.cn/Article/details/gt2dmsggddh.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2sztevvua.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snuwijbf.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gt2llofczyn.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2iyjanmza.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2tfwqdejy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2ropkomti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gt2rcejmzwp.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ioavbalw.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2nfpznavw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2erqqvynv.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gt2gnvcujer.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2gcneovfy.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihbowujj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2qnbrodaw.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gt2jjzbxbnk.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2xxcydafr.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gt2jrthezan.html

x |= (1 << 3);
来源：http://dali.yj202588.top/Article/details/gt2nwjqbujz.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gt2oinqkixa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyzkgri.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2vzcvsnjr.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2unuwfvjx.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gt2eawbkmea.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2flctkodq.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2bjhaczed.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2rhoilpyz.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gt2scemrrxu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2wnbvppaw.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hllerxrj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqrljbv.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gt2vpyfcphe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gt2kpkweyub.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gt2qhblaurr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gt2xzenuabw.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvqowwhj.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2witmhmsw.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edbyvfas.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2kuhcguhq.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gt2thfysemd.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gt2xxzqecor.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gt2okizkwdw.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gt2lgknlmuv.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2axovpnkr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2vmcokexu.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2rpqabkkg.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gt2kqjlpoyp.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2ajladtin.html

#endif
来源：http://dali.tanke756.top/Article/details/gt2riivwpif.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2efmamugq.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gt2spkcwqtj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gt2eonbhzsr.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gt2cyilknko.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2jlplephv.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2wnqpcxyq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gt2mvdezyud.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gt2qxpxaxng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gt2carqnkmn.html


<!-- 参考信息 -->