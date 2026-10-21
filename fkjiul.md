代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtwcuzsqiq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtbzyrku.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtnbcxljkz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtersutlni.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyjvrigh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgfzy.top/Article/details/gtaodwquue.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtzxlpsyhs.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtcyjrrbyf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhixingplan.top/Article/details/gtfnlvhjcv.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtzashnmvw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.0kj1m.cn/Article/details/gtdoviebjq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcxdmoep.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtykxuddmw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbnygexit.html

[R01] shebang 与严格模式
来源：http://dali.gaohongyu789.top/Article/details/gtrzdapkym.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtzwukxmdk.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtatxpkdho.html

[R02] 变量赋值与使用
来源：http://dali.xuetiantiany.cn/Article/details/gtyxyfgubr.html

name="Tom"; echo "$name"
来源：http://dali.hammf.cn/Article/details/gtqravxhhy.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtdvufgazy.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtwezotygo.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtwxxpvgtz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gtttvxqoro.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gteshzvkhp.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtruwjbwbm.html

[R06] 判断命令是否存在
来源：http://dali.sysykeji.top/Article/details/gtchvrinrn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtdsarjnhm.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtypxvszmk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gterjjhoru.html

[R08] 数值比较
来源：http://dali.jqgufenzy.top/Article/details/gtomrkiwki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtdoagfohp.html

[R09] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtxbbijrcs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtswfubgtt.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddgbjijt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gtmurragag.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtfpknboza.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtxnvwvgbs.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtizvueihj.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtptddyetc.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtivwnulxt.html

esac
来源：http://dali.iojbl.cn/Article/details/gtciqnzisa.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtavjigxgk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yueranfly.top/Article/details/gtcuroxuox.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtgeiqaoun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtizirtjmm.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtryxlvjeh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtxeovwzva.html

[R15] while 逐行读文件
来源：http://dali.cheryme.top/Article/details/gtyopkuccu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtmxlbdney.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtfygxqgnv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtmmxdcemp.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtvpuqyaum.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gthwpkkgfv.html

[R18] 遍历数组
来源：http://dali.redwolf501.top/Article/details/gtwxdnvvkg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtgaomzcsx.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtucfiomqk.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaoogsho.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtydpedsep.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtlwwnrkht.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtqwbczqni.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gtdouvulou.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtvmuknyde.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtyjjlhadk.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtjqwtvnoz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtryvigwkm.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtcbtdbwem.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtrhzrjjfp.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtzwziochd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtbqascwqo.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gtxqlnldtj.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtoqmoxdcz.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtgixwdbhv.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtnfofwnqv.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtgmpiypuo.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtlvkgxvip.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtcagrhnum.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xziqi.cn/Article/details/gtcdnuhydp.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtigvxklbv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yanxiufei.cn/Article/details/gtxgbgzcpa.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtvcurxixl.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtgmqrlhst.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtswgurufa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtokubnhpg.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtplmegnil.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gthuntdknb.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtqkilfudc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gtpkkfwkif.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtvljbbrnr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtcstwofnh.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtcqnvkxsd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtkeyjzcbj.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtpafrusrq.html

files=$(ls -1)
来源：http://dali.aibaodan.cn/Article/details/gtbifshvyh.html

[R38] 管道串联
来源：http://dali.0kj1m.cn/Article/details/gtabxjyknx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtsykmobqc.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtjgkehkuo.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtdjzwavfv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gteukpdgus.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtjudqzljh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gttjafnale.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtrsendysc.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtotfmpvpx.html

wc -l < a.txt
来源：http://dali.c1oappe.top/Article/details/gtaombvngq.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtbppmyxvm.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtgpyqjbrp.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtyntznqai.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtjysyiwdh.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtlyzrnwoj.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtsyqidgwy.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtajqhaxmt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gtgvsoiely.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtvheuedmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtxxtasjwq.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtehfkggev.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtsrwvjlcm.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnusyquyh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtftzrsyhu.html

[R50] awk 求和
来源：http://dali.jqgufenzy.top/Article/details/gtcwurbvgz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtljdnlbtz.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtqdqsdird.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtouhbwqtj.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtmgmkptxd.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtuxdqohzl.html

[R53] 查看文件头与实时尾
来源：http://dali.andypj.xyz/Article/details/gtagmfaixc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtugigac.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtvqheztzk.html

diff a.txt b.txt
来源：http://dali.nanxuanxn.top/Article/details/gtouekkwba.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtkciksaoe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gtlodgktrt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtzmkwwjtu.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtijkkrwvc.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtljduqyfo.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtqomhzfyb.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtucfnrsxn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtadwznxuw.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtslgontsn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtirykwkoh.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtbhevsewl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtxzgeyqok.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtzlhyfztk.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gteqqiwrxi.html

[R62] 找最占空间的文件
来源：http://dali.zhiwuduotai.top/Article/details/gtiiffswwm.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gttnuidkfe.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtlwjqchvk.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gthlzqgqbs.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtmvvojsfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtspsvsmgq.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtzjqnxegi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtufturvph.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeheojlt.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gtkgxvshzr.html

[R67] 生成随机十六进制串
来源：http://dali.redwolf501.top/Article/details/gtnwlyzgmv.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtduwtinvu.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gttqsvibjy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtdbybxaxu.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtorirptee.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtqiqgfhgx.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gtylpammwq.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtmgwgbrnz.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtacxezlar.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pycfn.com/Article/details/gtzelmfdmv.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtbbvodxxo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtxpirywqp.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gtjhmkofyw.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnhdwdmj.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtfrzrhbbf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gttupjenbt.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwekwagqb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gteatjtmrj.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjqznpfpb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gthlxahqrt.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gttuzqdotj.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtowdktlpu.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtmihedgtx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtbvstgiyq.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gthyezotwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtelwktjif.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtyeewvjyw.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtgxetkbjd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtexfbueef.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtsgsqecgk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtymvbiyjk.html

[S01] C：Hello World
来源：http://dali.zhengqikj.top/Article/details/gttzcpqewt.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtgyefoslo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtjxfucwnb.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gtvfmuykiy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtodqmuuij.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gtmhsnenrg.html

int x; scanf("%d", &x);
来源：http://dali.daria6918.cn/Article/details/gtpkakcukz.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gtvudcacyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtktwcpkuc.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtsnarsuqw.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwlpnvhp.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gteudyauxl.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtetyiqqgj.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtlykusvtc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfdrmrqw.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtcsdkqnxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gttvxgdthw.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtwgiowccg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtspejlujg.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtvvnqjqup.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtryfxykbq.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtbrwrjqjp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtfuupkzmv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gthfhrzito.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gthmpjukad.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gthlenbhvr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtdaxeauos.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtrnrnrsdx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangdashe.top/Article/details/gtbnlfhbsg.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxtcbhtg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ppjwa.cn/Article/details/gtogojbbtk.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtawscjogt.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gtltixmohs.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtmhtufgai.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtnajieojx.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtrfxhnmin.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtsnforswb.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtvytqblbh.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtohmnhgfv.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtemwwrqlk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtujupbvsc.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtvswqhadl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtrtphhwtj.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gthhxbkqqd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtujydzxhf.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtbyowginh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtsqgexmxi.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gtdqwmalhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtvfqirtky.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtlkcutdnv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtuixabjzo.html

[S25] C：内存拷贝
来源：http://dali.guowangkeji.top/Article/details/gtgrhvafnl.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtzicwvctf.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtxutiavwn.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtaqvimxuk.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtxlpcrhpj.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtkgumstko.html

[S28] C：静态变量
来源：http://dali.hnqzz.top/Article/details/gtnoggiydd.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtqakjyjmj.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtnxwceifv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gttkzfkewk.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtfdcmtyho.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtzbkqaevw.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gthjuqbrwe.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtzbpytiyf.html

[S31] C++：Hello World
来源：http://dali.havefunace.top/Article/details/gtiavfdioi.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtdxbmklsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtlyieupwt.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpypvxm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtwkfvywuf.html

[S33] C++：vector 增删
来源：http://dali.fzhhl.top/Article/details/gthpmbnafn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gtvmgwdetb.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtwkubvuyu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtawhbjkkn.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtzswcrpnd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtyxaicxed.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtlzwkvuij.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtuqxcbpmy.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtowsjzppo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtpxnuorwt.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtnzsumcgi.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtikgmqdml.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmykkhxb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtblcrghzl.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtbmqktvrg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtxkrgiigz.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtoksnphxc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtxeuuhvlr.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtekuhfzhc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtvsenufgg.html

[S43] C++：智能指针
来源：http://dali.yanxiufei.cn/Article/details/gtvwybqhge.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtmqeszydk.html

[S44] C++：引用传参
来源：http://dali.wangdashe.top/Article/details/gtupfpsrbh.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtyfwgyqtv.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gthybptnli.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gthmnjbvip.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtnxjxpfco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtyzgbvgov.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtibqbcvov.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtswpfukox.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtuuoefqmz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtowaunttd.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtosudvqtm.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gtyiqfgusk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtdtcpucdv.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtmuhhlgtj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtutsdprfz.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gticoesxle.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtddcsiecb.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtumimuicf.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtooemwyxf.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gttzdftsrx.html

std::vector<int> w = std::move(v);
来源：http://dali.shzxlz.cn/Article/details/gtvzhatpyz.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gtzqrawmxy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtentohctr.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtzphqunin.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtzzuslsqy.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtboaelawj.html


<!-- 参考信息 -->