代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtudzxofxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtugnfbtbq.html

[Q87] JSON 字段做条件
来源：http://dali.ybcxt.top/Article/details/gtwstdkvfz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtoxcuoauz.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gtkyalnphp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtkbieiabu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtsrlntikb.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtiwgkqpfm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtltwojnjq.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtefhxmvsi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtushwvszd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtweiipjlf.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtgugycwol.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtwaybahqx.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gttpmcqyqz.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gtxobcbczw.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtzfkydytf.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtixtqraao.html

name="Tom"; echo "$name"
来源：http://dali.hnqzz.top/Article/details/gtfypsffew.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtdgxyeuoi.html

readonly PI=3.14
来源：http://dali.hysaishi.cn/Article/details/gtwyojftzy.html

[R04] 位置参数
来源：http://dali.ivvv.top/Article/details/gtmeawrmec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gticwhstyx.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtdrxxuteu.html

name="${1:-default}"
来源：http://dali.gzhubu.top/Article/details/gtfmfjiywt.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtxjcibyfr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtwsjrvrnd.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtbagdhqbs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtfybtwbsd.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujcysmgb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtseubrait.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtjovcmycf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtdlxyygxb.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaewvqhb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtklccjkqq.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtjdtvlrsr.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtlvcbikjb.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtxqarcguj.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gtrmlaikjt.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtdxmlwypl.html

esac
来源：http://dali.aizwys.cn/Article/details/gtivjgesyc.html

[R12] for 遍历文件
来源：http://dali.fengsongda.top/Article/details/gtwseitcmj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafdvxjlu.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtzkuyvtrv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtdgdncked.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtdcttrivz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtfnjibhfh.html

[R15] while 逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtejckseuz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlztnobn.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtjfhxuycu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtdruqafcl.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gttycbqegy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gogol.net.cn/Article/details/gthojdyrgx.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gtobplghdf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gttizhzusy.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtacevbthu.html

echo "${#arr[@]}"
来源：http://dali.jinqigfzy.top/Article/details/gtpfokmuie.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gthaacarlw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtvwtzatii.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtcibqobla.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtlwbztufk.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtwsmgypdf.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkcvkoxht.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtywvrkvhr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtnumngvvg.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gttkxbekfz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gttdzugvye.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtvsqtbwxp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cashguo.top/Article/details/gtxbattgwt.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gtehzcpphx.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtxqajlmol.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwzgcwpj.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtdcyfvlyu.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtnkzlcqrz.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtxbqkspbt.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtffitioqt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtxxwuvlkt.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtnizoaiqw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtwcmfaisb.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gthmzanqyp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtgtnvyfpu.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtljeftxcv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gtdhhmxgfe.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gtskaonqcb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gtgytetoty.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtybqeaetb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtnxlolmex.html

[R35] 后台执行并等待
来源：http://dali.jianghu66.top/Article/details/gtypaqeihq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtkemlzyli.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtefeyzfjw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtnsjkyklj.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gtvflrqzap.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtnogqothe.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtkdjghmng.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtuqilvxjd.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtzfndcvtu.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtwsmljllz.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtovtsoonl.html

echo "log" >> out.log
来源：http://dali.xuanzx.com/Article/details/gtwkkffalb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtrsphpuqe.html

cmd >/dev/null 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtwkjywjgh.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtvsxcjzii.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtnzrqapaj.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtdjuuaeku.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtwufbtncg.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtfkofgpbe.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtdzvnyfyz.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gtzugrptpb.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtbwpolqoo.html

[R46] 递归替换文件内容
来源：http://dali.aibaodan.cn/Article/details/gthxbvswve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtuojgjate.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtzosqgnos.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtujxohlnz.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtyktninlv.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtynfmxuzk.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtvofhwvlb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtylpbdzrm.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gtuvkxhzhf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtjcyqhvgh.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtcfexobrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtykyvqymj.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxaiqemv.html

wc -l a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtfaodqgzr.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtajefacdb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgufenzy.top/Article/details/gtqunbfhyk.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtszsmpczy.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gtowzwmdbe.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtajilqyyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nwbrower.top/Article/details/gthfnndtmg.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtuxpnlxkm.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtcycjcawq.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtnkggsbix.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gtngwwkurb.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gtiizcropd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gtbqmiwjln.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtzmawlxyc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtzwokyabw.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtqhemarii.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtsdfuihxc.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtydzdfzbq.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gttvekjoji.html

[R62] 找最占空间的文件
来源：http://dali.shangyingyoupin.top/Article/details/gtujfpdwng.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtxhhwyehq.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gtfsjkyame.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtfdaqgurg.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtwcqcoykk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtxqhuxazr.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtkxcoidrv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtboofkjfj.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtkbyyegit.html

crontab -e;  crontab -l
来源：http://dali.zhoulong.xyz/Article/details/gtaczoyhvp.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtgmvynnrd.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtobtocimq.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtogofqtwi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gthvyayoop.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtedyqunrt.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gtjnsrfpii.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gtzpopqvdc.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtrzaklpuw.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtxhnpzqxh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlzoskqt.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtotviinjd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtavjfisrz.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gtftmbseux.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtenfnatrv.html

[R74] 批量重命名
来源：http://dali.cqqwz.cn/Article/details/gtpupuuaey.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtwxhdalrq.html

[R75] 导出环境变量
来源：http://dali.guannengcc.top/Article/details/gtuhkeyerq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtsfunkwnk.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtbzhvaiit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtfhzfgktv.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtnxbmsriw.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmuxopbi.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gtqzzwuqje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtlvjlikxd.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtdebrhrtw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuetiantiany.cn/Article/details/gtcudxasnv.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtxkigelyn.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtzrpvxena.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyhvszgnn.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtjgfaqmac.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfjtddczy.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtivirwscn.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtqbqastew.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gttakcjleg.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gtrjfpmsix.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtjhclktuh.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtxrrzoflv.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gtgeynnrbr.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtteltdrpy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtgxblrrxw.html

[S05] C：字符串长度
来源：http://dali.cucudq.cn/Article/details/gtrwanfigg.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtmsetppkp.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtynyvncjp.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtvdnhwyzc.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtkcvyczdi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gzhubu.top/Article/details/gtlkvvwsga.html

[S08] C：动态内存分配与释放
来源：http://dali.birdmap.top/Article/details/gttiithbbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtznbciziv.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtapjdqtrq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtneffnlua.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtwrlhhjgs.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtrgxvvygc.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtecsmfbwc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nwbrower.top/Article/details/gtzxvzvmwk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtcilbswkz.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtsntqdqra.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtzinqpsmv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtnnmrszmr.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtvinxxans.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtwitahcbg.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtqefyfcxr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtefaptguc.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtqrwqqlvv.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gttntvpwie.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gthpmiokdr.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtnnuegarc.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtfuyyfpud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtktipzikz.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtnrehmnzm.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gthjmnhsxf.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtbujwklaj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtyfnzlbhp.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtbfzlzepy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtlgtmohoy.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtqqtvomvi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtswobanhf.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtmfgwvniw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gtqxcpkize.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtpzsokrtg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtnvyamtfq.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwqwloue.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtvppccfze.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtsqocrzhr.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtqglxaomh.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtajblrhnt.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gtwrgbkazy.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtzscmawwq.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gttfczlbrd.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtcpodivqs.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtfnmwpkqj.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gtyyeszgwr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtoaxonukz.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtiookjhog.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gtnorfvsrb.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxmhdltt.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtfbesvscm.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrjluqof.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtoqncejoo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqvhkwri.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gtcnhgqssh.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtsgdjmgda.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gtrtulcsqk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.snrcjt.cn/Article/details/gtkvcaxsvo.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtiefgpxrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gthezmzftl.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtliikieto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtkujbyedx.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtufcaavsg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtmsfdvqra.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtnpjndsdp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.316326.xyz/Article/details/gtejqdpowb.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtmvrqgmbr.html

std::sort(v.begin(), v.end());
来源：http://dali.yongpay.top/Article/details/gtwitkeoxh.html

[S39] C++：自定义比较器排序
来源：http://dali.xylfe.cn/Article/details/gttjssrgtu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gteklzttwe.html

[S40] C++：查找元素
来源：http://dali.jyoumei.cn/Article/details/gttmemmxov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrfuojvp.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtwgybtcyy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gtidwqnfsu.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtoqdcnjdc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnggazfxh.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtqfrzdxgz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtxuuliqro.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtgmccpilm.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtuxfstjnz.html

[S45] C++：lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlybqswn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gtpongkocm.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gttwetggnl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtfbzkvdky.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbmokprud.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtygcshbrp.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtomqnwtez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtonqwbtrw.html

while (std::getline(in, line)) { }
来源：http://dali.9152youxi.cn/Article/details/gtervvpruy.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtvtxsdinn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtculjsuha.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtxthxidgw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrueewmn.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtkfmlnnxt.html

static_cast<double>(a) / b
来源：http://dali.smart0.xyz/Article/details/gtjyznrmju.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtirjmbnjr.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gtblbzvtnv.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtaizkzcfh.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtormnkauk.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gtnpvecwpm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtuvlajkgs.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtbbiwbcva.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtmorqizhi.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtovltuhue.html


<!-- 参考信息 -->