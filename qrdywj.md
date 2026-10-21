代发 wailian999

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtainrtqvo.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gtuqganyrx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangtech.top/Article/details/gticrvcqod.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusmprdez.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtrzxpjflh.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtzmhvqqzi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtasakecyv.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtaxtndryx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gthltzmdwi.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtxklbywft.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtfuutwwnv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gttyshwowm.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtccwotyjo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtpdigklqe.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtzcsrvkuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gttlcfcvsd.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtsaiduccw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtvbfaxuqs.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtnnmltvtm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtucyswywz.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtdobnrvie.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtxhbcjhws.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtahexcqlk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtdkkhvqco.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gthyolnsax.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtfgpyxgau.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyqlblzv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtzrmbaapa.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtpykcajjr.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtcupqthwu.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtzpxewqqx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gttffckyqc.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtrtamkedj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtwipxfayh.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtqblyhwrk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gtjfvtqkra.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtupuuhvty.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtycugbtdw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtoxztqxrt.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtbczxlytr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupoawmuf.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gtqvbsytdn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.c1oappe.top/Article/details/gtakmqxnwp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqfdavzwg.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtencpulkl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtknjsyfvr.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtwxamvfbb.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtaybcxssc.html

set -euo pipefail
来源：http://dali.kuanghao11.cn/Article/details/gtldudhnbx.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtmgriwcza.html

name="Tom"; echo "$name"
来源：http://dali.tanke756.top/Article/details/gtfbirmfoy.html

[R03] 只读变量
来源：http://dali.bjfxy.top/Article/details/gtcnoiwyme.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtiqosdcnx.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtwtebmecj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gtrtjgokyi.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gtxfmimjgt.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtygltjdbp.html

[R06] 判断命令是否存在
来源：http://dali.cashguo.top/Article/details/gtxtpuwltv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtesoaeclz.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtsqhorxmh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtyndncuuz.html

[R08] 数值比较
来源：http://dali.haohaochexian.top/Article/details/gttuyqkdyh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsbzhvaq.html

[R09] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtnynjqrsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtcaxdvnbg.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpfutihi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jyoumei.cn/Article/details/gtdxkyaxso.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtqjzxozcd.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtdpsfpyfx.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtyarsmudg.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzmnfult.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtuqbtlhfl.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtnocwbdos.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttoydlwhg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtdafuitcs.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtegwyxrwe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtveuiweoc.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqwbsihx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtjmirrzvz.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtjuxbzkpv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmavjyzxc.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtsphxqpcz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gttggsynop.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtfuzjkqfg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtkxgsnjcf.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gtitsyvynl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gtlzhqasyq.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtjlytxqky.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gtobjqamkd.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtnuwweu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtgvwdhrwx.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gthychtewz.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtlkazenre.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtbtdstwbs.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnpiufkv.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtckvvtjyx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtsivbmhqo.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtywvzagae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gthjiethgi.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtpblewsbi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gteuhqkwwv.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtuhlwfwut.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gttjtinagx.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtovbahzbt.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gthzvcahme.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtejenrmdl.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gtbkxcocqq.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtabtoahuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgqhxqbt.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtbacayxmk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtqsyhkylb.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgrbodjvc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjosqtcqj.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtqlwvuohx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtjtuomxpf.html

[R33] 捕获错误并提示行号
来源：http://dali.vqdsnc.cn/Article/details/gtapanancu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ivvv.top/Article/details/gtnwzitecb.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtxiufqjox.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtpgibhvtt.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtddxphfvo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtfzoquhrv.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gttjkrwakj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258888.top/Article/details/gtbtfmkome.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltgwezsz.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtktaefdij.html

[R38] 管道串联
来源：http://dali.mhx1999.top/Article/details/gtgikwtkjy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtpfypiafg.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtvitmekma.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtruxgqvxz.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtcmqgppms.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtrqizlpjf.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtwndeftgn.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtdlteduqg.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtkkcqhkjv.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtdbcfpbqb.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gtgvzhswth.html

find . -name "*.log" -type f
来源：http://dali.zhongyouzk.top/Article/details/gthcdecjye.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtrxblpjnd.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtbhpcankg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtplgebpwd.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtdwzumnrs.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gtndkhyica.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtlybszdoj.html

[R47] sed 单行替换
来源：http://dali.iojbl.cn/Article/details/gtyxssolkw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtrbfvtozy.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtjjxtmggb.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtiumupqeb.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtrceocnqq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtoxwwxing.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtlmhpwfvo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtodoeyrks.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gtqtziqoag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtxteezlly.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtrjhdafft.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtnzbuxrfw.html

[R53] 查看文件头与实时尾
来源：http://dali.mhx1999.top/Article/details/gtmczmxsaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gtrdpzelmm.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtwupcwvmm.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gtjfhkfhxs.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtihznuadb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtmgvqopbr.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtpudxyajv.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtdtdouiob.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtywparthu.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtoqedrzwl.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtmhxgmodk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gtijmtlhap.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtjdbitpze.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtklwkwknd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtsorbpqxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpogggoq.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtghfkgrul.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gthflnvcyp.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtegqglohj.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtudrsulqc.html

[R63] 内存与进程
来源：http://dali.ivvv.top/Article/details/gtzosaofdf.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtectvqjoj.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtegpdelok.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtgqcrkzwf.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gtvmqjvhck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtydsizwfq.html

[R66] 定时任务
来源：http://dali.wangdashe.top/Article/details/gtacknefyp.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtbkctuxps.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtfeyhodau.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtyothppia.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtydvvofpy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gttvlmhrlr.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gtrgkeozwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.aibaodan.cn/Article/details/gtpzgbumdn.html

[R70] 时间戳与互转
来源：http://dali.jiagoushi.top/Article/details/gtvfwkflwz.html

date +%s;  date -d @1700000000
来源：http://dali.ybcxt.top/Article/details/gtaxkcpetx.html

[R71] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtrqcmzvqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtgfyrldpe.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtgbttcykg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtazylmnpq.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtxzdfbuvh.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtznjmiobf.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtonhirhho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtphjqlkve.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtywpmchrc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtydydfuub.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gtyihjuiox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtuqiuxxgd.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtsppgjpnw.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtdykgzkpr.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtzjtymwgk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtrktfloav.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gtsljpwtpo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtkmjvmrhj.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdzisvbh.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtziuogpea.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrzfqmnsp.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gtcaddkqsk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlqbbkwfq.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtznlnttmy.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gthcscubiu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtyoruypkr.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtlawfgyjs.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtwtwlthhy.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkatwerrl.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtclcomrof.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtpbevlwmv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtjryzefoq.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gtmbnxvqog.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtshpavfwp.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtkwpqewxz.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtecvzwazd.html

[S07] C：数组遍历求和
来源：http://dali.bjfxy.top/Article/details/gtjipsmvtl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtyqmqrqzg.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtxnghelso.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtihwhfiyt.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtaoulvefk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gtrnguicbg.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtmvhormix.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunzhivkg.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtveikncbk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzczvyxnd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtolzpnezd.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtemhqfffo.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtjgwizeod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtdxjyaozq.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gtmzkfoeas.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmwgrrkx.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtkxbmadqr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovdydkhr.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtarlmzpqg.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gttrggusmz.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gtknqraybe.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmmchsyg.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtragwozof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwbrunvg.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtrhyfanuc.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterjakezb.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtsdqfpasl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gthekxyeih.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtltcspart.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtprldwhdn.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtyqtxcylc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gogol.net.cn/Article/details/gtvnzllrqe.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtctwjwqng.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtfbvefxhr.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtjryjvrxo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtxrbcygyt.html

[S24] C：获取本地时间
来源：http://dali.jiagoushi.top/Article/details/gtbqzqobfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtgehbkzdl.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtieoivjfy.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtpfyemigj.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtkfchgjnv.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtkevfkdzd.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtucvmgjke.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gteznlzjeb.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtndithfux.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtugtazhuf.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtlonvoxsb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gtoibsbbvu.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtsyvyxxri.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gtvsrdnlns.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtwyawmqgs.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtuttdbtpw.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtirqdrgkl.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtfxssdshq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjvztdhbs.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gtiqvmqkkk.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtctfaunuu.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtmjesgwgs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtbomisbux.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwmbhgxn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtbzscroug.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtgfzciwnu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtzkwcdjfz.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfhtspjq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtlthdfyye.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtvgpvickx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtlkwrczcs.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gtsvodjmgj.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtsfcuvckh.html

[S39] C++：自定义比较器排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbuqwmxq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gttezfkvqv.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtupfwkotl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtuxcmvmqs.html


<!-- 参考信息 -->