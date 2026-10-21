代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtpukqfnxh.html

SELECT TRIM(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtxpvvpspu.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtlkgtvmay.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ehwqpu.com/Article/details/gtditmqumf.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtgxolfqpx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtltbteilr.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtnntnwuoh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtumjpmqrg.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtattjirda.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtrtlivhfl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtgqxcyxod.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtvzxahody.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtpweeqpmv.html

[Q90] 生成序号列
来源：http://dali.pengpengdd.cyou/Article/details/gthwcqmnhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtvdntsbco.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtojhzqkeu.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gttpyjhczg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtomlqhuar.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtqvhjupkv.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtcygolfnj.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtvkuusjqo.html

[R02] 变量赋值与使用
来源：http://dali.yongpay.top/Article/details/gtehfkqtod.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtxtstatdl.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtaealndgd.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gttuxnuspm.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtselsiwxv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.svipenyu.cn/Article/details/gtlfmucqgq.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtehcwbcrz.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtqlgyvfmi.html

[R06] 判断命令是否存在
来源：http://dali.bjfxy.top/Article/details/gtdghejftg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtksasllpv.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtxcucyion.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gttageonmp.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtzxocxsjb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtxgsooosh.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtgqmeggcl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gttlwcqoqq.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gtwyuiaxrd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtupczbqvs.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtnrllyjgo.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtglivytzv.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtyudegjpk.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtwxukfrpw.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtohgwxdow.html

esac
来源：http://dali.redwolf501.top/Article/details/gtpjjckawg.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtdnkdhkwv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtezpewsnq.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gttcxhgppz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtswbrnrdd.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtdosemffz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgfibsvtw.html

[R15] while 逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtcwcrzlak.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtepkjomgi.html

[R16] until 等待条件
来源：http://dali.yongpay.top/Article/details/gtrcwgkmfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gthrpmqnwl.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtqxkiftor.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtvknxclmm.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtqqozdfmo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gttooenqyd.html

[R19] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtrzkmnohc.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtdxjtxyap.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtayslbqyc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gtonempjzc.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gttqlevowg.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtiowfmtci.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtlizwpjup.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtdmdhpyjg.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydvguyhq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyxvdmdt.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtjncfgdwr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtrlcwydtr.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtviexdqof.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtwgvfdwti.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtfvsjwsnu.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxuanxn.top/Article/details/gtquzarzps.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtiwgzkxfb.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gthwksywgy.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gtegtpblnt.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtpysndjtn.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtvjsqkypt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtrerudepq.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtddraaoqp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gtdnzjvguo.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtiqfjpbyx.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gtazqtoitm.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtqsuqcxra.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtcadifdcw.html

[R33] 捕获错误并提示行号
来源：http://dali.pycfn.com/Article/details/gtcfvgatca.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sysykeji.top/Article/details/gtakndmmqz.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtannytvna.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtqervpzew.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtazderyya.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gtgjnyvnkd.html

[R36] 并发执行多个任务
来源：http://dali.yj20258.top/Article/details/gtwtnpdbzr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtcbvyseil.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtkbwknetp.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtaryhqqpm.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gtrdoeqpvb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gthpewekkk.html

[R39] 重定向标准输出与错误
来源：http://dali.ivvv.top/Article/details/gtdqdazids.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtunzmkgzc.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtfxjgsbgv.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtxnvuhncv.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtvwwumyvq.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gtkxvmapjf.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtxhljyhux.html

wc -l < a.txt
来源：http://dali.yj20258.top/Article/details/gtjhoxfolh.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtjmtjpkdg.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtmkbiocwu.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtqudbvecm.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtfkzqxwim.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gtilmkqsic.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gteftndewl.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtkbwfnrmp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtizvhxcff.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtuxcvqdan.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtxifpikuv.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtumpwvlor.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtbpmagnqq.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtgkrudqsl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gteoddabck.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gtzmfbonty.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtltwveilo.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtwprznlcq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gteovpdofq.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgcpnhqx.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtpofvfocj.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtwrhwhzpq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gticaibwhn.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtfornqxhi.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaltecra.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtmuqwrwjo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtyyulqsjn.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehxeiyhe.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtbmrwzusq.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtfwpgmedl.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtgpjdtvna.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtpspwhfte.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtqrolyhja.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyoaaqty.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtmjrcxtrm.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtiimqinfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtfcapdikm.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtlrpnrmnd.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtuvfpnqhq.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtzudgmjdf.html

du -ah . | sort -rh | head -10
来源：http://dali.jiagoushi.top/Article/details/gtfevdxeuf.html

[R63] 内存与进程
来源：http://dali.yj20258888.top/Article/details/gtfoxkzjna.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtinufcwgn.html

[R64] 结束进程
来源：http://dali.yj20258888.top/Article/details/gtlhlgsiby.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtpqzcgnun.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtrxrgvcea.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtlnqqruti.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtmsjtzaem.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtpazztrln.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtrjjcypvt.html

openssl rand -hex 16
来源：http://dali.9152youxi.cn/Article/details/gtnjbpjhmk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gturslldqb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtzzgjduiz.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gthfpqvzyn.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtzjizpxoh.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtxaveoicc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtdoxyxloh.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtfhexiqqu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gthbbhyymq.html

[R72] 等待端口就绪
来源：http://dali.jinqigfzy.top/Article/details/gtodpapznb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsyliqcas.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtdciescei.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtopniskwv.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtqpgazkub.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtzkgjpxdw.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtlyaldhla.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtynepbzhr.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtooypevyo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gtmosykzeu.html

[R77] 读取用户输入
来源：http://dali.yuxming.cn/Article/details/gtmfwnqzrq.html

read -rp "请输入: " ans
来源：http://dali.iojbl.cn/Article/details/gtpuudxzmq.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbkavzol.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtwopicdkk.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gtupkzkztw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtksjvzcyl.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtzqephzhs.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtnfqjagci.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwvhrlusw.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtxxdcztmi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoeapmofa.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gthahxhmya.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtccttxtsy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gticepukhx.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtvrmdsbgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtsmopxsop.html

[S03] C：读入整数
来源：http://dali.sweek.top/Article/details/gtzmyclnfl.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddtzokep.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtwnaxlllj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjbuzvps.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtnvlxzujc.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtmojynhpx.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gtdnhhykbq.html

strcmp(a, b) == 0
来源：http://dali.xuanzx.com/Article/details/gtvzppalca.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gthxrbiriz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtktdfekde.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtjzsdxlpb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtvjalrggh.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtpiihkjul.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtwxymwabv.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gttlztpgkd.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtbqinturx.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtdvjftquv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtfeubfibb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aibaodan.cn/Article/details/gterjgayob.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtprftagqb.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfxvesuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtsmzgqosf.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtfzczbhri.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttfkytgb.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtsdadjrhb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pengpengdd.cyou/Article/details/gtlpqyycbv.html

[S15] C：类型转换
来源：http://dali.yj20258.top/Article/details/gtenpgnprb.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtpqknbnyw.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gttghmpdbr.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtahxynmmr.html

[S17] C：安全拼接字符串
来源：http://dali.ivvv.top/Article/details/gtnhywumrr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemjrajdx.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gttkjldijb.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtydzbwukh.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtqzmiclus.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtzwjsswwn.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtqlfowcbn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtzhitxeic.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtbkynuxdm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuswelvc.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtzykbwhyd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtkbldczgi.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtmwnmrlcy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtqttsafnu.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtsjbmgioh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtjorlhfjr.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtjxkzsvfi.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtjuzgegqp.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtzygrayyk.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtjocsgdhi.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gteqenkfsa.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtlfeclbev.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtepburdlj.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtbmorhdnd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gtjvleqpit.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gttaesatkw.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtpsbhwatb.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtuisqxjif.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtmqrojlwb.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtjzvjzbxw.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtllfrqcjx.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtrozsthrn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtvbvdshiu.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtzpdcbqpz.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnxoqtpi.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gthfztwnim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtrqmroxhm.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gtwmcnlvip.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenlongwang.top/Article/details/gtguciizah.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtdbjltnlp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtqwbkuvtw.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtyfhgckmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtmoovugfj.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtttngltxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtduxnmuxm.html

[S38] C++：排序
来源：http://dali.smart0.xyz/Article/details/gthlhjdyhq.html

std::sort(v.begin(), v.end());
来源：http://dali.316326.xyz/Article/details/gtzehykgzk.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtogmemdvq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtvdbebmku.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtqfnpmjdh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtsuazxxbe.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtwiivjlhb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtvjtbttux.html

[S42] C++：继承与虚函数
来源：http://dali.316326.xyz/Article/details/gtszemazdp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gtzxxsatbh.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gtqugqsvhh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtdhcqjdzo.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtxtsnniuv.html

void inc(int &x) { ++x; }
来源：http://dali.hongshengwenyu.top/Article/details/gtegcpiqku.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtnmngeebn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xziqi.cn/Article/details/gtrsfznoxm.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtoqcnvkfv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtyapxsegc.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtwcjcctbj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtcndfpwrh.html

[S48] C++：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtkbdosuuu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtykktffmx.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtyziybsfa.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtvpzktkts.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtivwlbcjw.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtczmwefey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtyjcgftos.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtzhgozdth.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtffjnonmx.html

[S52] C++：const 与 noexcept
来源：http://dali.aizwys.cn/Article/details/gtmifatowm.html

int size() const noexcept { return n_; }
来源：http://dali.hnqzz.top/Article/details/gthffueejz.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtizufpnxw.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtapkjrlmg.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtyewxmhhl.html


<!-- 参考信息 -->