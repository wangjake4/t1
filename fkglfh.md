代发 wailian999

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gt2dcumvfvr.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2xsnesokv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gt2nkcdeght.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gt2ywzpakjo.html

SHOW INDEX FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2dycquote.html

[Q73] 查看表状态
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhjfiavc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtmosgyv.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gt2mdlpgvsa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2ieheakmt.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2nqfcdtxy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2uzvlitei.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.quarkkingdee.top/Article/details/gt2bbtwiuhf.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2rgyodkou.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhngwohu.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gt2chegwoab.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2nkheboxt.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gt2vupbosmu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gt2lamgekdb.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gt2efsgtolq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gt2bttduwhm.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gt2igwowztx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvwbmqwq.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gt2tohajlmy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2dngpbnsk.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gt2ttkrvahn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2wdokccio.html

[Q83] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgnnihgn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2czrmruaj.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gt2ujtqcuxe.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2fbqdcbkg.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnumsuwk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gt2mgpqhkcs.html

[Q86] 读取 JSON 字段
来源：http://dali.316326.xyz/Article/details/gt2ykxxblsz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gt2hcucbnzy.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gt2urzxyxay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gt2haqposgn.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2rgjwzaqc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gt2eleqscxj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2semkrjnm.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2bjdyweud.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hiifiduu.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gt2kthdzhwf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shzxlz.cn/Article/details/gt2dlgnlxjp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jogudzps.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gt2ewvytknc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2mitcqtox.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgrdfp.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gt2olclphbo.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gt2bookotch.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gt2zjlphvyd.html

name="Tom"; echo "$name"
来源：http://dali.chenzaomai.com/Article/details/gt2whbpkyzw.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gt2paknfsno.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gt2kbhsoukv.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gt2nfcsupiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2vyufrbwj.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2pmpumfnz.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gt2ietpwjfy.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2bovnkvso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2axlkxhyz.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2krhnvucc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2hxhzudhk.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gt2yehmzgft.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gt2ymzhicef.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2xecbnsuz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2nujtmmoo.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2wjdwftzv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opmvtmxe.html

[R11] case 多分支
来源：http://dali.jyoumei.cn/Article/details/gt2csygkwib.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gt2xxkhbebj.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gt2lpprvqwb.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gt2ckssmxlu.html

*)     echo "未知命令" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2elvooizv.html

esac
来源：http://dali.guowangkeji.top/Article/details/gt2oimcqffk.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2hsotzbga.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gt2scwgmwda.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gt2iiywmvyx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2agzyeeei.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2yctemgau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjnigutc.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2cuologsp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2zhzrbzwp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofijplif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2qyusbkhr.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2atqezsux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gt2onskgall.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gt2vdtpmxmu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gt2tvpmprud.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2flpsstzs.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gt2uqsohxbh.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gt2tlsosktf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2cfzaiywt.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gt2zovirwsg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivstbovp.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2qnttdbfl.html

echo "${s:0:5}"
来源：http://dali.zycfv.cn/Article/details/gt2rzjuueaa.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2arompoum.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gt2aktgrnep.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2stnteood.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aizwys.cn/Article/details/gt2enzjzquz.html

[R25] 去后缀 / 去前缀
来源：http://dali.cashguo.top/Article/details/gt2tlnbpest.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gt2cwnknpji.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2mzpnqyyb.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gt2uvysrpac.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2ckeipudf.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2phnzoiue.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2psvizhxu.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gt2ozxdkewy.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2xaxtoqfc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2gyqadqho.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gt2vqcqqkqf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gt2qgqzrucg.html

[R31] 局部变量
来源：http://dali.yonumen.top/Article/details/gt2pcpqhaxs.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2xheakcoa.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gt2hococmnc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2elpnzagp.html

[R33] 捕获错误并提示行号
来源：http://dali.hfpthk.cn/Article/details/gt2gjrdtbwy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gt2budausrw.html

[R34] 退出时清理
来源：http://dali.yj20258888.top/Article/details/gt2fycjatqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2hxfrxiyq.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2fbovtgeq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cqqwz.cn/Article/details/gt2oofexljt.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gt2xzphurkc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvwvalnf.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2ejonoytq.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gt2dszxmgho.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2gwesnsyk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gt2hidyrcgq.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2axofpvue.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gt2fjusogki.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2fwkwgbiv.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqgkqgvt.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gt2mgosmgzk.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2timzckbk.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2bfxouljn.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2thuhakni.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gt2gfxidbsl.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2zewdvtpp.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2hebujxin.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwwqnxmn.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hndjrizm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2taigdoel.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gt2lfcxdkxv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gt2qobnplwd.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2nhjerpui.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2moztmnnm.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gt2muvlajrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdmjyadk.html

[R49] awk 带条件
来源：http://dali.yj20258888.top/Article/details/gt2lkuwlxbp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gt2pwbpbiig.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjvwbpmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqrrgzwd.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2oqceygeo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2gyqwphqx.html

[R52] 统计行数
来源：http://dali.zhoulong.xyz/Article/details/gt2fmqrjayp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ombqvfym.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gt2yrthffxg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gt2gytwerfm.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2srlybpup.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvnpxywa.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqbnpvgi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gt2dzjiyoyr.html

[R56] 远程拷贝
来源：http://dali.guannengcc.top/Article/details/gt2xvuvzpcp.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gt2xmcuemul.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gt2dnnfzmvh.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fztdtvbm.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2mojphkha.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2qmpxgtan.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kpglqrxb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gt2zrlqtpbe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2dqobvgnu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nwbrower.top/Article/details/gt2pitdpkyv.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2nvqcbxns.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gt2qcakjgwh.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gt2vvdazard.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gt2ajjoyymf.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gt2qmlymlen.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gt2zmhavzzu.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gt2gbkdjkpb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2gbiplhon.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2gmqfqdti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gt2meumzlak.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afhcjxcm.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zywbjeul.html

[R67] 生成随机十六进制串
来源：http://dali.cdnleiting.top/Article/details/gt2qlaoanvj.html

openssl rand -hex 16
来源：http://dali.zhiwuduotai.top/Article/details/gt2jljplwks.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gt2ftuhmrnt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrxtmaiq.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gt2bwynsvec.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgfzy.top/Article/details/gt2oxaulbzd.html

[R70] 时间戳与互转
来源：http://dali.yj20258.top/Article/details/gt2yscuvbci.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gt2puegnhhr.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2uqrbtfvf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2milafhcm.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2vxtlawjq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gt2aylvvlzl.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gt2swrnrtdz.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gt2xaqbzjyw.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gt2srsfjths.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2worvosuj.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2kxvzjibt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2wxaxkpfn.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gt2ungfdxwx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2vdhqvivj.html

[R77] 读取用户输入
来源：http://dali.jyoumei.cn/Article/details/gt2viqklioq.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkuyldbh.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2urarhctx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gt2ykpvfuwp.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2raydluob.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojmwjoyj.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gt2lveizylp.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gt2nhqqxfpv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dengaelb.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2bneoywrn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2cxzlntji.html

[S01] C：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2gsbgeddq.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gt2wjxvdwse.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qlljxzoh.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2xqslkxkr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2ryczhuwz.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2sgqdvwwb.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkfesrmw.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2idiblpqt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2flinvacu.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2awlvjytm.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2xhimczpa.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2umciuoec.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2knseiaig.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2caqxzwsr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.c1oappe.top/Article/details/gt2uwcifibp.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2bhdsbxfj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2zoibliba.html

[S09] C：结构体定义与初始化
来源：http://dali.haohaochexian.top/Article/details/gt2fvedcjgz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gt2flbtvxtd.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2pcwcybzo.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gt2ltxdwswu.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2vkzvaned.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2lovmhhxu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2erfyjcaw.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gt2yklpnngn.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xofdaetw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.svipenyu.cn/Article/details/gt2pflajhek.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gt2yunsssmh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gt2zrlmblqz.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gt2uovvulvn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2koifhwhj.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gt2tdxaijee.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gt2rzjbcrfl.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gt2rybjkhro.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2teucexdf.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2fmtgfxpm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gt2obsawjhb.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2whxzimhn.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfxcngms.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkphfzbp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2qjsdnhdo.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gt2chbqwzlg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gt2sihmyzfq.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2ltnkmmih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gt2cmlttdon.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gt2orabtwhd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gt2freefdkg.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2cfpomrfk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gt2jcvajtid.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gt2vwjhjxal.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gt2kuyudbcs.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2iegmgemd.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuoozrhh.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gt2mkaxbzgr.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmblsvoy.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gt2ufrrdnyc.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2ouayqfse.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gt2qqdohxbj.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2eadtmrpk.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gt2mynwfbrt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2qxfilhqb.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gt2ctizvzqd.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2fwuwxyxg.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gt2skcxoukw.html

#endif
来源：http://dali.meibo888.top/Article/details/gt2xomknitp.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2rgyedpmp.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gt2mupepjpz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2xxcgviyz.html

[S32] C++：字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgdvbktr.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2oysmkmwm.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gt2rszishxa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gt2payefvte.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gt2gqoobdne.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gt2ueitpypk.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gt2wqdszokj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpwxthsr.html

[S36] C++：unordered_map
来源：http://dali.ppjwa.cn/Article/details/gt2mpbxaayu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmebrsda.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2chasqpfm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gt2icabadlf.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2uayieyqz.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2tncwjjqu.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gt2luahvhgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gt2xfklocve.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gt2urfpisyz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gt2qmdjbfia.html


<!-- 参考信息 -->