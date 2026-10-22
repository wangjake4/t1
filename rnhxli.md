代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.gaohongyu789.top/Article/details/gt2yqzqbpci.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2tudpsduh.html

[Q85] 数值取整
来源：http://dali.fengsongda.top/Article/details/gt2jpyfjfzs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.redwolf501.top/Article/details/gt2jlrruzdw.html

[Q86] 读取 JSON 字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmpdjfjg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxklmkdq.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gt2xxaktxve.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gt2wmedlvvs.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gt2hnexvbdv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2cutaugom.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2buelecsg.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2sluttcoo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gt2ybkrczjz.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gt2tyjxrzrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2fgdvmgfl.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2rpluuyzv.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gt2dhiwofot.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kazskwuv.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2oqqgcxxc.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqdzrjrj.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gt2fotgiinc.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2ytjpnzie.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gt2tupuouzw.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2iinivayf.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2rwswelps.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2nxbafaap.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jianghu66.top/Article/details/gt2epkgimwu.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gt2vkhrqppl.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2iqmsxgpd.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2hzvfefqh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2fjjdmmgq.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gt2tyyfreqy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gt2vypeumjm.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2mmfigfux.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gt2opavgzod.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gt2jcsgiztf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2kxpjqolw.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gt2qhpjpljr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cheryme.top/Article/details/gt2nrhunkyi.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gt2khjbbsrh.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhddbuot.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gt2pofaulhn.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2snoohant.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gt2lqabembr.html

esac
来源：http://dali.kuanghao11.cn/Article/details/gt2bvwbrbtf.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2vxvdgbjt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2cfynsdge.html

[R13] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2qdwlqybc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2pgdbalrz.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tyclbngn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2pduywifj.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gt2jtnfduxd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gt2xcdkamrj.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2maxewoxm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2zyizwgon.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2pearsgzt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gt2xpamutfz.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gt2ssjvrpal.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gt2iusceujz.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2abetzjqt.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhfxgfcw.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pstnayqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2fahjosyg.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2isqqwkuy.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2jsvnzsdj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fblxpyaz.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2xcrrmxem.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2jkqmzikw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gt2sryakbjr.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2xkmrxpbm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gt2opdshqjh.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gt2ciqnyvtu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsgzqljj.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2ekjjyeoe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvacvcze.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqedsyyp.html

echo $((1 + 2 * 3))
来源：http://dali.tianlin.xyz/Article/details/gt2pihqkwfh.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gt2bxrpjtpt.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2pnmgfwkk.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2jawwihnd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2pufjktch.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilqksvpn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zycfv.cn/Article/details/gt2uwqofqgo.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2itnrgbyu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dfwdniow.html

[R32] 参数个数校验
来源：http://dali.9152youxi.cn/Article/details/gt2zrxbxekp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2vupcqwse.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2dxjuxptc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gt2chnstwct.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gt2krvleoqd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gt2utahsjfa.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gt2ipemdcas.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sweek.top/Article/details/gt2ecofeyrs.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2ackukfqu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gt2sjepzehb.html

[R37] 把输出赋给变量
来源：http://dali.fzhhl.top/Article/details/gt2nalajkjr.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2seznodjh.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gt2npftorma.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gt2ionenkvn.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gt2gkwhiesf.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2nxdjrtib.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gt2lcjifntv.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2vjcryhzt.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2hxrpmvir.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2ifjbitqc.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2rkfkuxjp.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2nwvglyal.html

[R43] 按名字查找文件
来源：http://dali.shzxlz.cn/Article/details/gt2qqcguxnv.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gt2sznfowjt.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gt2hvzvoufs.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2zgjdqfli.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gt2hqvhpfdg.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gt2wowqekaw.html

[R46] 递归替换文件内容
来源：http://dali.fengsongda.top/Article/details/gt2ntbggnvn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gt2ukrqmrut.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2deupxxno.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gt2jmlzvwwh.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2imqroyvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2abuwuqwi.html

[R49] awk 带条件
来源：http://dali.vqdsnc.cn/Article/details/gt2cydtmygm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gt2nhubzich.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duloorlb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lalvpxoq.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gt2fljnoyfk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj202588.top/Article/details/gt2cbkctylw.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gt2vlpfzgzy.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gt2cnchkyao.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gt2jtlaimsi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gt2rhiszcfs.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2bhjbialp.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2torkujcf.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gt2nwtzprnt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2vdzbbddx.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gt2nmqrxeet.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gt2tthsbfvp.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2nqakztue.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gt2mghzsdnv.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gt2kugcvgmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.havefunace.top/Article/details/gt2sygftndh.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2rymflfrw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gt2jmnkmxvr.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkdhoewd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gt2wbbnffkc.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gt2uscrdbbf.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gt2nyawehum.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gt2cbzxlava.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gt2gucwitlf.html

[R63] 内存与进程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psjdgdcm.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gt2gikgyedl.html

[R64] 结束进程
来源：http://dali.haohaochexian.top/Article/details/gt2qqfydclz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gt2ecgfklio.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gt2rifnherl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gt2svqodivt.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2molqyyro.html

crontab -e;  crontab -l
来源：http://dali.chenzaomai.com/Article/details/gt2mditucnq.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gt2tidjstno.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2blvflzrj.html

[R68] 计算文件校验值
来源：http://dali.dashuyun.cn/Article/details/gt2jqmqmqqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2jcihdlkp.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gt2jwgsbgcb.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtzwumot.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2vyshqelx.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyzmkfjr.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2aagdkiou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gt2oduwzxpm.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2ihwiqtgp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2rdhpefzx.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2fkhongiw.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gt2xwtmmqkf.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gt2qffgiiga.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2aeokzbqf.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnoasevm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gt2rvisvusn.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gt2pttabgkm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2alfkadie.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2ejafhxcn.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gt2sidjuurv.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gt2ornmyihs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gt2uwqyzcpk.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gt2eceqhbar.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfkunjlw.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmbhawvt.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2ujllmlev.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2gactmabv.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gt2jodtaydq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2liwjoqev.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2karhbggw.html

#include <stdio.h>
来源：http://dali.hywenlv.cn/Article/details/gt2xtrcntwq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gt2rfagaeau.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2qammqooo.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gt2ynstvvoa.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gt2tlnqykcn.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxkwhbtw.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdqhxzab.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gt2btlurujm.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bemlctls.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gt2zyardvlw.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2ugzshpij.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2gkblhoaf.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gt2zaeaspzb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2etdqaeuc.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gt2kedauidh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbnxfpmp.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gt2rgnzvcnx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyawwhii.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gt2vpjgiauc.html

int *p = &a;  *p = 5;
来源：http://dali.fengsongda.top/Article/details/gt2wwzugzpe.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2bvzefnqz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2ulhdifmm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2ahcamjwd.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2xipzrgkj.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gt2tpuwurxu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gt2njqtnjjl.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2drcpjxti.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2nxtyhfeh.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gt2cfqzatqm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gt2paxlamok.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tsvkzhty.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gt2hxfkntse.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2lmlnddqu.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gt2pgrorliu.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2nvghxmmz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gt2txipxkwx.html

[S18] C：命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2bqykncxj.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2pmjwejpq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jcptzsbt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2dhvogstw.html

[S20] C：二分查找
来源：http://dali.ybcxt.top/Article/details/gt2wvnmqxni.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2aibxakfu.html

[S21] C：字符类别判断
来源：http://dali.quarkkingdee.top/Article/details/gt2smmjxkjq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gt2xdnwxzbo.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gt2nyrdyohy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gt2xonarago.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gt2dbkefbcu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2mywdyxtv.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gt2lqqjilwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jianghu66.top/Article/details/gt2ecapmgfd.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2fmakzitn.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gt2drepqskr.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gt2vuoxhdbx.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gt2tupoivad.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gt2yitebjxz.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2yzpcmmzj.html

[S28] C：静态变量
来源：http://dali.yj20258888.top/Article/details/gt2hniibulb.html

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvrobeol.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gt2xxbavnen.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gt2wajlxhou.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gt2mxxtobrt.html

#ifndef X_H
来源：http://dali.yueranfly.top/Article/details/gt2rencyajh.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blluogop.html

#endif
来源：http://dali.wangdashe.top/Article/details/gt2sclaxqfo.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2ghhqejah.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2vqjthdcf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2hhssmmxs.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gt2pxwhpisc.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gt2wvsshwon.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hvegqdhv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gt2nojulthx.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2hotnyoon.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gt2qtpdauib.html

[S35] C++：map
来源：http://dali.hywenlv.cn/Article/details/gt2swmndjay.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2xcjqffww.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gt2dukrqoih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2tmboidfc.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2fppmgqeb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gt2aqqvvitb.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gt2gpoayapf.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2fkcgbthl.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gt2kqyzwfkz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gzhubu.top/Article/details/gt2nbukvjnr.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhtxvcyd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2okzfmjgb.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2czcdskma.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2lkyuwowd.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbkycckg.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcekxeap.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gt2qvlkunto.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2sbinmttg.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2mhgdwump.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgrhthje.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gt2hxejaklu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2mwjclnru.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxrtifmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pfoeoewa.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gt2onurkcab.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2vmynrmjs.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2wjyevqfr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gt2lbjqkiiq.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gt2pevaaezk.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkzfyqqs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gt2qbktwnbb.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2xfseigxb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2opnitplo.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gt2uzfwodgt.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2zmrmlsuh.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gt2lpnukqnq.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gt2lgondxrq.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gt2zhbfdjte.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gt2jgmaewbp.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2fqsdqoqt.html


<!-- 参考信息 -->