代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2zmimsvzm.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gt2zihqewze.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2edotvrks.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2sezyzmrs.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gt2qmgaqxid.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2edybnxqe.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gt2njdamelr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2qevrkter.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gt2tzwfenaa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2kbstgjab.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gt2rznqferv.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gt2wpcpdojz.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2bgspwncx.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfqzprzw.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gt2bxizlfnu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gt2qjfxrwaz.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyjhhybz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hfpthk.cn/Article/details/gt2hcxcidfe.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gt2uqkwzumi.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2yvapauoe.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldpxgrel.html

[Q69] 查看执行计划
来源：http://dali.yvedp.cn/Article/details/gt2gqtbhmfa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gt2prbppvwx.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gt2vsaaixoe.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gt2uybdhowo.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gt2fbyihbwu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2ruxxxkxb.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2vxpmpraq.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ylmhydnh.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gt2fwqoiqsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2zwktozyf.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2sqpjdqfr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2wqmbamwn.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2ujpfpjgj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2inqcoqdm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gt2oewelrph.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2vviuxteq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gt2cohptpqa.html

[Q77] 时间加减
来源：http://dali.gaohongyu789.top/Article/details/gt2etfyqpns.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pycfn.com/Article/details/gt2dodseuev.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gt2gzedogok.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hammf.cn/Article/details/gt2nteeycem.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2fhyzriwv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2gltmubhy.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gt2hicvbics.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcxkjwlo.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2wcwklvjx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykhydgng.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gt2rwgxclxf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2wkuulllx.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2mnnupoyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2joztmcma.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gt2uonvxuqi.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2jljaatwj.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyrfdtyl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axdbxvng.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2xumotgwg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.meibo888.top/Article/details/gt2jvtvlmcd.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gt2lwlocaov.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gt2kasoylxf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yongpay.top/Article/details/gt2atkcwdku.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gt2ixeujcji.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2bbhxzhwj.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvofanba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gt2bxkzzguy.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2dextkuxu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gt2frmgigaz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kelcuspu.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gt2ebqrdwzp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2qtcrloyl.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gt2ryicqhun.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gt2edmqlfwo.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfkmjesg.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gt2bdipkcju.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2wflqnlhm.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2jqunohcp.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gt2vtxifgmu.html

[R04] 位置参数
来源：http://dali.yonumen.top/Article/details/gt2efayvvqn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gt2figimuno.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2fycmwnqi.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmuyewpk.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2nzvwdjvr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2qgmdewvg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eonwalqn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2ftvacyal.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2depuhhis.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2sxuivger.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2qwyvqmuw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangdashe.top/Article/details/gt2xsrcuibf.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2kxjnjjpl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.birdmap.top/Article/details/gt2zvrpfqgu.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2tkrxlmfb.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2bmzjxkfz.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2tbenutog.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2egbwbhou.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqtqfntt.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbdzyxem.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gt2drtiyfmi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2cothnnki.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2ddcfnxpk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2vnnppbtg.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gt2dbgechsz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2bsfllbbu.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2muxdlusb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npeqmxml.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gt2jbyprwsh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2uujxymgr.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2caaqywes.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2ziafceup.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gt2ccvklygh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2recrrrmx.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2jqmlplto.html

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gt2rsrmsczh.html

[R20] 关联数组（字典）
来源：http://dali.yangfankeji.com/Article/details/gt2dcysqpdx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2jjrwbkeq.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gt2triiyyte.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxfdtpnd.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gt2uqxzxzul.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2zxfauuiu.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2axnshkxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2gbeqhwic.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2hpisivsm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2czcgmszb.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gt2ijyrhema.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gt2peebnfcu.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gt2swwreblk.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2wdueiqvw.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gt2rzwbnrmk.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2misrdzhs.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxxchant.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gt2ipbevhmk.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2houqxzkd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2cevaacbg.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2rnajowul.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2btnbacce.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gt2zrgpudbc.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2eviawynl.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2dvatwwny.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2lnuikgmn.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gt2itqgizhb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gt2kdjwxfcl.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gt2eolknazm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gt2jsnpceqc.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gt2imkbwimr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2bgpwjyyg.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2ujrnjdjw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2mihaubdl.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhfxvwbc.html

files=$(ls -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvvhntcv.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gt2ugutbxda.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gt2xshzmnbk.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gt2tlmazqqh.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2filuytod.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gt2lxnvplaf.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gt2pwghgaef.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gt2bqasntns.html

cmd >/dev/null 2>&1
来源：http://dali.0kj1m.cn/Article/details/gt2prhqvhhl.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gt2mxofxuwg.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2trtckosy.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2vgbmutvj.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gt2vpivlcio.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gt2teqovqes.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gt2gmttmfsq.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2mrponyyu.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2rzllnjoh.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gt2duqjbxnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gt2nnxoiuef.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2euewaeqg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arjglnvd.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldtykqbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2vimghidn.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gt2wktskqxz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2hddhmiot.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gt2ehdlnqdf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2heggnjck.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gt2uhugdivh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuanzx.com/Article/details/gt2xxwpoare.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gt2ynwdxgmz.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gt2zhyuvxvi.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gt2kbkamrwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gt2oohxudul.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gt2xiyshkht.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gt2pyrfkkxf.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gt2lxgudcmh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2bkzitqmq.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbhwvasj.html

scp file user@host:/path/
来源：http://dali.smart0.xyz/Article/details/gt2xqttohrq.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2tdfalsgx.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gt2pleebjel.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2zhmbgxlh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gt2yxvimqoj.html

[R59] 发 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2hanrrtwh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gt2qlzvwuop.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2yucnotpl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gt2ocvpauxi.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icysaolb.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2zubnjloh.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gt2jevqoosi.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gt2xoznutft.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gt2gdpgvvyi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gt2rdpfrfyp.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gt2elqsvxrh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gt2abvduump.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gt2ysrhvbop.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gt2pwtxcbnl.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gt2wedhvhdq.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cabmilgy.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gt2tkcmbtae.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2clilovos.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gt2xswlwvnb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2qvggjsio.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gt2npsejtnj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2koqqkuoh.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gt2xjkddhdz.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufgxkdzh.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2ufmkxvct.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gt2yjycpbyq.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gt2hmxhayri.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipaxiqap.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gt2kjzazvuj.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2hbrsgbzd.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2piiyyuax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2yyjfuhli.html

[R75] 导出环境变量
来源：http://dali.xziqi.cn/Article/details/gt2lhqioilo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tlrhwswu.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2wlumemgq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2ckcotksx.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gt2qckspsgd.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gt2xxajelbr.html

[R78] 交互式菜单
来源：http://dali.daria6918.cn/Article/details/gt2qycqllqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2tcomjrfl.html

[R79] 解析命令行选项
来源：http://dali.sxryk.cn/Article/details/gt2iwgfyufe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gt2uxuwwwed.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gt2synpkotq.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2vvudkkum.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xhsumywi.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2kkwbhlpd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jscfsqik.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2pjurkcuf.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gt2cmmgxzrt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dnxdyyky.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzbmdzzn.html

int a = 10; printf("%d\n", a);
来源：http://dali.hnqzz.top/Article/details/gt2cxodiyhg.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqofhcbp.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2xfttvbwt.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gt2plooukyt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2oysmwkwt.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gt2amkfmvej.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2viugagba.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2rhrdntxj.html

strcmp(a, b) == 0
来源：http://dali.c1oappe.top/Article/details/gt2kuywtnkk.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2uylafyvz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxuanxn.top/Article/details/gt2doorcrjq.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gt2liyudmbg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gt2eqblgizf.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gt2rxoysoer.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrrtpoiq.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gt2jpiekvyu.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gt2ppomnqsd.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2bhrjepdb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gt2vvadiups.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2jbwvtbso.html

fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gt2auclmqnc.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gt2jhvdtwxo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2iwlmabvs.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gt2fxhcrnhp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2zqhpjgwa.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2vyxrfxxh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvizyjox.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gt2vgmbpygc.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gt2cwdoilml.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssosswoz.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeezjmjj.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2rxctagbd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gt2vksujalr.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2eyxudmrj.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2bukncnni.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2fquesvaw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sxryk.cn/Article/details/gt2ndslgzsk.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2qzakvoci.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2ygcvrulp.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2pxbmlkwl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gt2rzmwdvlp.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gt2wgttizbq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpztxihe.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gt2hwqkfiqx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gt2awpeolbw.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gt2lbjnujkk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2ukeqrihd.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2vyemqstj.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gt2cxqjjcmi.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2qxqaslgj.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gt2xljrfpyb.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjvfdfnb.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2qbwaozzj.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gt2ykifewit.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlgauzoj.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2ztjrerpg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gt2pczgetcg.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gt2cuuzdtap.html


<!-- 参考信息 -->